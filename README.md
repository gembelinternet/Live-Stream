# Live Stream

## System Requirements

- `OS` : **Linux** / **MAC** / **Windows**
- `node` version >= **v16.0.0**
- `python` version >= **3.6** with **PIP**
- GNU `make`
- `gcc` and `g++`
- Redis Server
- SQL Database

---

## <img src="images/Express.js.png" height="130" width="130"> <img src="images/plus.png" height="60" width="60"> <img src="images/Sequelize.png" height="130" width="130"> <img src="images/plus.png" height="60" width="60"> <img src="images/Socket.IO.png" height="140" width="140"> <img src="images/plus.png" height="60" width="60"> <img src="images/Firebase.png" height="136" width="100"> <img src="images/plus.png" height="60" width="60"> <img src="images/i18next.png" height="140" width="140"> <img src="images/plus.png" height="60" width="60"> <img src="images/redis.png" height="140" width="140">

---

## Modules

### Translations

- [ ] Import translation
- **Available translation**
  - [x] EN (English)
  - [x] ID (Indonesian)
  - [x] AR (Arabic)

### User

- **Sign in / Sign up (manual)**
  - [x] By email / username
    - [ ] Send verification code
    - [ ] Confirm verification code
  - [ ] By phone ( SMS / Whatsapp )
    - [ ] Send verification code
    - [ ] Confirm verification code
- **Sign in / Sign up with :**
  - [ ] Google
  - [ ] Facebook
  - [ ] Instagram
- **Authentication method**
  - [x] Cookies
  - [x] HTTP bearer
- **Authentication Session**
  - [x] Token validation
  - [x] Renew token
- **Account recovery**
  - [ ] Recovery by email
    - [ ] Send verification code
    - [ ] Confirm verification code
  - [ ] Recovery by phone ( SMS / Whatsapp )
    - [ ] Send verification code
    - [ ] Confirm verification code
- **Account**
  - [x] Follow & Unfollow
  - [ ] Block & Unblock
  - [ ] Report
  - [ ] Profile
    - [ ] Board
    - [ ] Following & Followers
  - [ ] Voice types & voting
  - [ ] Suspend
  - [ ] Ban
- **Wallet**
  - [ ] Transaction
    - [ ] Top up
    - [ ] Gift
    - [ ] History
  - [ ] Withdrawal
  - [ ] Status
    - [ ] Suspend
    - [ ] Ban
  - [ ] Deletion
- **Security**
  - [ ] Password bruteforce
  - [ ] Device manager
  - [ ] Force destroy session

### Live

- **Room**
  - [x] Create
    - [ ] Category
    - [ ] Tags
    - [ ] Privacy _(public, private, friends only, followers only, invite only)_
  - [ ] Publisher mute / unmute
  - [ ] Participant mute / umute
  - [x] Enter / Join
  - [x] Joined user / listeners
  - [x] Chat
    - [x] Send / Receive
    - [ ] Markdown support
    - [ ] Tagging support
  - [ ] Notification
    - [x] Joined user as listener
    - [x] Joined user as participant
- **Privileges**
  - [ ] Mute
  - [ ] Kick
  - [ ] Freeze
- **Gift**
  - [ ] Send gift
  - [ ] Display gift
- [ ] **Ranking algorihm**
- [ ] **Broadcaster**

### Notification by Firebase

- [ ] Subscription manager
  - [ ] Subscribe user notification when following
  - [ ] Unsubscribe user notification when unfollow
  - [ ] Unsubscribe user notification when blocked
- [ ] Push notification
  - [ ] User live
  - [ ] Private message

### Ranking

- [ ] Live
- [ ] Cast
- [ ] User

### Store

- [ ] Products
  - [ ] Crown
  - [ ] Sticker
  - [ ] VIP
- [ ] Top up amounts
- [ ] Currency
- [ ] Payment Gateway
  - [ ] Midtrans
  - [ ] Doku
