# goit-markup-hw-02

      <form class="footer-subscribe-form">
        <div class="footer-form-field">
          <label for="user-email-link" class="footer-label">подпишитесь на рассылку</label>
          <input type="email" name="email" id="user-email-link" placeholder="E-mail" class="footer-input" />
        </div>
        <button type="submit" class="button-footer">Подписаться</button>
      </form>

/_ Футер подпишись _/

.footer-subscribe-form { display: flex; width: 570px; height: 86px; margin-left: 93px;

align-items: flex-end; }

.footer-label { font-weight: 700; font-size: 14px; line-height: 1.14; letter-spacing: 0.03em;
text-transform: uppercase;

color: var(--main-white-color); }

.footer-input { width: 358px; padding: 15px 16px 15px 16px; margin-top: 20px;

border: 1px solid rgba(255, 255, 255, 0.3); filter: drop-shadow(0px 4px 4px rgba(0, 0, 0, 0.15));
border-radius: 4px;

background-color: transparent; }

.button-footer { display: flex; margin-left: 12px; padding: 10px 28px 10px 29px;

font-weight: 700; font-size: 16px; line-height: 1.88; letter-spacing: 0.06em; align-items: center;
justify-content: center;

border-radius: 4px; border: 1px solid transparent; color: var(--main-white-color); background-color:
var(--accent-color);

transition: background-color 250ms cubic-bezier(0.4, 0, 0.2, 1), box-shadow 250ms cubic-bezier(0.4,
0, 0.2, 1); } .button-footer:hover, .button-footer:focus { background-color: var(--btn-hero-color);
box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.15); }

.button-footer::after { content: ''; width: 24px; height: 24px; margin-left: 10px; background-image:
url(../images/icon_send.svg); }

.modal-form { width: 528px; padding: 40px; }

.modal-title { margin-bottom: 12px;

font-weight: 700; font-size: 20px; line-height: 1.15; text-align: center; letter-spacing: 0.03em;

color: var(--title-text-color); }

.user-contacts { display: flex; flex-direction: column; }

.user-contacts:not(:last-child) { margin-bottom: 10px; }

.user-contacts input { height: 40px; padding-left: 10px;

border: 1px solid rgba(33, 33, 33, 0.2); border-radius: 4px; }

.user-contacts textarea { height: 120px; border: 1px solid rgba(33, 33, 33, 0.2); border-radius:
4px; resize: none; } .modal-text { padding-bottom: 4px;

font-weight: 400; font-size: 12px; line-height: 1.17; letter-spacing: 0.01em; }

textarea { font-weight: 400; font-size: 12px; line-height: 1.14; letter-spacing: 0.01em;

padding: 12px 16px;

color: rgba(117, 117, 117, 0.5); } .user-agreement { /_ width: 425px; _/ margin: 10px 0 30px 0;
text-align: center; }

.modal-agreement { font-weight: 400; font-size: 14px; line-height: 1.71; letter-spacing: 0.03em; }

.agreement-link { color: var(--accent-color); }

.button-modal-submit { display: block; margin-left: auto; margin-right: auto; padding: 10px 55px
10px 56px;

font-weight: 700; font-size: 16px; line-height: 1.88; align-items: center; text-align: center;
letter-spacing: 0.06em;

color: var(--main-white-color); background-color: var(--accent-color); border: 1px solid
transparent; border-radius: 4px;

transition: background-color 250ms cubic-bezier(0.4, 0, 0.2, 1), box-shadow 250ms cubic-bezier(0.4,
0, 0.2, 1); }

.button-modal-submit:hover, .button-modal-submit:focus { background-color: var(--btn-hero-color);
box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.15); }

      <form class="modal-form">
        <button class="btn-modal" data-modal-close><svg class="icon-close">
            <use href="./images/sprites.svg#icon-close"></use>
          </svg></button>
        <h2 class="modal-title">Оставьте свои данные, мы вам перезвоним</h2>
        <div class="user-contacts"><label for="user-name" class="modal-text">Имя</label><input type="text" name="name"
            id="user-name" required autofocus /></div>
        <div class="user-contacts"><label for="user-tel" class="modal-text">Телефон</label><input type="tel" name="tel"
            id="user-tel" required /></div>
        <div class="user-contacts"><label for="user-email" class="modal-text">Почта</label><input type="email"
            name="email" id="user-email" required /></div>
        <div class="user-contacts"><label for="user-textarea" class="modal-text">Комментарий</label
            class="modal-text"><textarea name="text" id="user-textarea" placeholder="Введите текст"></textarea></div>
        <div class="user-agreement"><input type="checkbox" name="agreement" value="agree" id="user-agreement"
            class="modal-agreement" /><label for="user-agreement">Соглашаюсь с рассылкой и принимаю <a href=""
              class="agreement-link">Условия
              договора</a></label>
        </div>
        <button type="submit" class="button-modal-submit">Отправить</button>
      </form>
