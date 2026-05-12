# Bale Docs GitHub.io - Project Roadmap

## Overview
Creating modular, LLM-friendly documentation for https://docs.bale.ai and https://docs.bale.ai/miniapp

## Structure
- `/bale-docs/` - Root directory
- `/css/` - Stylesheets
- `/js/` - JavaScript utilities
- `/modules/main/` - Main documentation modules (docs.bale.ai)
- `/modules/miniapp/` - MiniApp documentation modules (docs.bale.ai/miniapp)
- `index.html` - Main entry point
- `README.md` - Documentation index

---

## Phase Checklist

### Phase 1: Foundation Setup ✅
- [x] Create directory structure
- [x] Create base CSS stylesheet
- [x] Create main index.html
- [x] Create README.md with navigation
- [x] Create module template files (3 core modules created)
- [x] Add .gitignore
- [x] Create ROADMAP.md

### Phase 2: Main Docs - Core Concepts (Modules 1-5) ✅
- [x] Module 1: ساخت بازو (Bot Creation)
- [x] Module 2: ایجاد درخواست (Making Requests)
- [x] Module 3: دریافت آپدیت‌ها (Getting Updates)
- [ ] Module 4: Update method
- [ ] Module 5: getUpdates method

### Phase 3: Main Docs - Webhook Methods (Modules 6-10)
- [ ] Module 6: setWebhook
- [ ] Module 7: deleteWebhook
- [ ] Module 8: getWebhookInfo
- [ ] Module 9: WebhookInfo type
- [ ] Module 10: انواع موجود (Available Types - Intro)

### Phase 4: Main Docs - Basic Types (Modules 11-20)
- [ ] Module 11: User
- [ ] Module 12: Chat
- [ ] Module 13: ChatFullInfo
- [ ] Module 14: Message
- [ ] Module 15: MessageId
- [ ] Module 16: MessageEntity
- [ ] Module 17: PhotoSize
- [ ] Module 18: Animation
- [ ] Module 19: Audio
- [ ] Module 20: Document

### Phase 5: Main Docs - Media Types (Modules 21-30)
- [ ] Module 21: Video
- [ ] Module 22: Voice
- [ ] Module 23: Contact
- [ ] Module 24: Location
- [ ] Module 25: Invoice
- [ ] Module 26: File
- [ ] Module 27: ReplyKeyboardMarkup
- [ ] Module 28: KeyboardButton
- [ ] Module 29: InlineKeyboardMarkup
- [ ] Module 30: InlineKeyboardButton

### Phase 6: Main Docs - Advanced Types (Modules 31-40)
- [ ] Module 31: ReplyKeyboardRemove
- [ ] Module 32: CallbackQuery
- [ ] Module 33: WebAppData
- [ ] Module 34: WebAppInfo
- [ ] Module 35: CopyTextButton
- [ ] Module 36: ChatMember
- [ ] Module 37: ChatMemberOwner
- [ ] Module 38: ChatMemberAdministrator
- [ ] Module 39: ChatMemberMember
- [ ] Module 40: ChatMemberRestricted

### Phase 7: Main Docs - Final Types & Methods (Modules 41-50)
- [ ] Module 41: ChatPhoto
- [ ] Module 42: ResponseParameters
- [ ] Module 43: InputMedia
- [ ] Module 44: InputMediaPhoto
- [ ] Module 45: InputMediaVideo
- [ ] Module 46: InputMediaAnimation
- [ ] Module 47: InputMediaAudio
- [ ] Module 48: InputMediaDocument
- [ ] Module 49: InputFile
- [ ] Module 50: ارسال فایل‌ها (File Sending)

### Phase 8: Main Docs - Chat Management & Payment (Modules 51-60)
- [ ] Module 51: Chat management methods
- [ ] Module 52: Message editing methods
- [ ] Module 53: Stickers
- [ ] Module 54: StickerSet
- [ ] Module 55: Payment introduction
- [ ] Module 56: sendInvoice
- [ ] Module 57: createInvoiceLink
- [ ] Module 58: LabeledPrice
- [ ] Module 59: answerPreCheckoutQuery
- [ ] Module 60: Transaction methods

### Phase 9: MiniApp Docs - Introduction (Modules M1-M5)
- [ ] Module M1: مقدمه مینی‌اپ (MiniApp Introduction)
- [ ] Module M2: مثال‌ها (Examples)
- [ ] Module M3: راهنمای طراحی (Design Guide)
- [ ] Module M4: دسترسی به مینی‌اپ‌ها (Access Methods)
- [ ] Module M5: مینی‌اپ اصلی و پیوند مستقیم

### Phase 10: MiniApp Docs - Implementation (Modules M6-M10)
- [ ] Module M6: پیاده‌سازی مینی‌اپ‌ها (Implementation)
- [ ] Module M7: WebApp object
- [ ] Module M8: متدها (Methods)
- [ ] Module M9: Header
- [ ] Module M10: WebAppInitData

### Phase 11: MiniApp Docs - Types & Events (Modules M11-M15)
- [ ] Module M11: WebAppUser
- [ ] Module M12: ThemeParams
- [ ] Module M13: BackButton
- [ ] Module M14: SettingsButton
- [ ] Module M15: Events

### Phase 12: MiniApp Docs - Validation & Debugging (Modules M16-M20)
- [ ] Module M16: اعتبارسنجی داده‌ها (Data Validation)
- [ ] Module M17: رفع اشکال اندروید (Android Debugging)
- [ ] Module M18: رفع اشکال نسخه وب (Web Debugging)
- [ ] Module M19: نمایش هشدار آپدیت (Update Warning)
- [ ] Module M20: مشکل پرداخت قدیمی (Payment Issues)

### Phase 13: Final Integration
- [ ] Create comprehensive navigation
- [ ] Add search functionality
- [ ] Test all links and modules
- [ ] Optimize for LLM parsing
- [ ] Final review and validation

---

## Current Status
**Phase 1: Foundation Setup** - In Progress

## Notes
- All content must remain in Persian (as in original docs)
- Each module is a separate HTML file for modularity
- Clean semantic HTML for LLM readability
- Minimal modern CSS
- No JavaScript dependencies for core functionality
