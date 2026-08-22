<div align="center">

# 🐍 PT HUB — Blox Fruits Script

> **PT HUB is back — created by PT.**
> Một script Blox Fruits gói gọn trong một file `.lua`, **tự chứa 100% UI**, không tải thư viện ngoài, không cần mạng sau khi load, tương thích mọi executor phổ biến.

[![Blox Fruits](https://img.shields.io/badge/Game-Blox_Fruits-0b0e17?style=for-the-badge&logo=roblox&logoColor=white)](https://www.roblox.com/games/2753915549/)
[![Lua](https://img.shields.io/badge/Written_in-Luau-2c2d74?style=for-the-badge&logo=lua&logoColor=white)](./Scriptload.lua)
[![Lines Of Code](https://img.shields.io/badge/LOC-14%2C471-48bb78?style=for-the-badge)](./Scriptload.lua)
[![Single File](https://img.shields.io/badge/Single_File-✓-facc15?style=for-the-badge)](./Scriptload.lua)
[![No Dependencies](https://img.shields.io/badge/Dependencies-0-22d3ee?style=for-the-badge)](./Scriptload.lua)
[![Made by PT](https://img.shields.io/badge/Creator-Pt-e85c6a?style=for-the-badge)](#-tác-giả)

<br>

**233 toggles · 105 buttons · 26 dropdowns · 6 sliders · 15 tabs** — tất cả trong một cửa sổ glassmorphism neon, có keybind thu nhỏ (`Left Ctrl`) và nút nổi cho mobile.

</div>

---

## 📦 Tải & chạy ngay

### 1. Copy loadstring

```lua
loadstring(game:HttpGet("https://raw.githubusercontent.com/hlpt411/Pthubv2/refs/heads/main/Scriptload.lua"))()
```

### 2. Dán vào executor

- Mở **Blox Fruits** trên Roblox
- Attach executor (Delta, Solara, Xeno, Wave, Hydrogen, Fluxus, Arceus X…)
- Dán đoạn trên vào ô script, bấm **Execute / Inject**
- Menu PT HUB sẽ hiện lên sau 1–3 giây

> 💡 **Menu ẩn/hiện:** bấm `Left Ctrl` trên bàn phím, hoặc chạm vào nút tròn nổi góc màn hình trên mobile.

### 3. Tải file trực tiếp

- File gốc: [`Scriptload.lua`](./Scriptload.lua)
- Có thể save về máy, upload lên host riêng, hoặc dùng trực tiếp trong executor có hỗ trợ `readfile`/`loadfile`.

---

## ✨ Tính năng nổi bật

PT HUB được viết lại từ đầu với hàng trăm module, chia đều trên **15 tabs**. Dưới đây là bản tóm tắt nhanh.

| | Tab | Mô tả ngắn |
|---|---|---|
| 🏠 | **Info And Status** | Theo dõi giờ game, full moon, đảo Mirage / Kitsune / Prehistoric, Frozen Dimension, bánh xe boss (Cake Prince, Rip Indra, Dough King), bộ xương, kiếm huyền thoại |
| 🎨 | **GUI Settings** | Theme Neonblue / Emerald Dark / Sunset / SlateStatic / SlateAnimated, animation, cửa sổ nổi, phím tắt, nút mobile, lưu config |
| ⚔️ | **Farming** | Auto farm level / nearest / all island, Elite Hunter, Boss TOTS, Cake Prince, Dough King, Soul Reaper, Ectoplasm, Bones, Berries, Factory, Pirate Raid, Materials, Mastery (Fruit / Gun / Sword) |
| ⚙️ | **Setting** | Bring Mobs, Fast Attack, Safe Mode, Auto Buso / Ken / Race V3 / V4, No Clip, Anti AFK, Anti Admin Join, Remove VFX, Auto Hop, Auto Set Spawn |
| 🎣 | **Fishing** | Chọn cần / mồi, auto mua mồi, auto câu, auto quest câu, tự bán cá, spam skill Z |
| 📜 | **Quest And Item** | Auto Colosseum (Bartilo), Citizen (Tushita), Yama, Soul Guitar, CDK, Saber, Rengoku, Pole V1/V2, Dark Blade V3, Midnight Blade, Twin Hooks, Serpent Bow, Bisento V2, Marine/Swan Coat, Usoap Hat, Lei, Rainbow Haki, Observation V2, Godhuman, Sanguine Art, v.v. |
| 🌊 | **Sea Event** | Tự đi thuyền, Ship Speed Modifier, No Clip thuyền, Auto Shark/Piranha/Terror Shark, đánh Sea Beast / Pirate Grand Brigade / Fish Boat, chế tạo Shark Tooth / Terror Jaw / Shark Anchor / Leviathan Crown / Shield / Boat, Scrolls, mua thuyền |
| 🌌 | **Mirage And Race** | Tìm đảo Mirage, ESP & tween tới đảo, thu thập Gear, nhìn trăng, Advanced Fruit Dealer, nâng cấp V4 cho Mink/Human/Angel/Fishman, kéo lever, train V4, race trial, tele Temple of Time / Ancient One |
| 🌋 | **Volcano Event** | Tìm Prehistoric Island, Start/Patch event, Kill Aura, thu thập Dino Bones & Dragon Eggs, reset khi xong, Dojo Trainer, Dragon Hunter, Drago V1→V4, craft Dragonheart / Dragonstorm / Dino Hood / T-Rex Skull / Volcanic Magnet |
| 📡 | **Stats And ESP** | Auto phân bổ điểm Melee / Sword / Gun / Blox Fruit / Defense, ESP người chơi, trái cây, rương, đảo, hoa, kiếm huyền thoại, haki color, gear, đảo sea event, Advanced Dealer |
| 🍇 | **Fruit And Raid** | Random / Drop / Store / Tween / Collect fruit, mua từ Fruit Shop, tự chọn chip, auto raid thường + raid nâng cao, Awakening, tele Lab, Law Raid, mua chip Beli/Devil Fruit, farm Dungeon với TP exit |
| 🦸 | **Local Player** | Fly, Speed Fly, Dash No Cooldown, Mink V3 vô hạn, năng lượng/soru/tầm Ken vô hạn, PvP, aimbot, auto kill player quest, ignore đồng đội, accept đồng minh |
| 🚢 | **Travel** | Travel East Blue / Dressrosa / Zou, auto đi lại giữa các sea, portals, tele tới NPC bất kỳ (có ô tìm kiếm + refresh) |
| 🛒 | **Shopping** | Mua toàn bộ fighting style (Buso, Geppo, Soru, Ken, Black Leg, Electro, Fishman Karate, Dragon Claw, Superhuman, Death Step, Sharkman, Electric Claw, Dragon Talon, Godhuman, Sanguine Art), vũ khí, súng, phụ kiện, reroll race, redeem all codes |
| 🛠️ | **Miscellaneous** | Rejoin, Hop Server (thấp người / ping thấp), tele Job ID, copy Job ID, mở Awakenings Expert / Title Selection, đổi team Pirate/Marine, unlock portal, RTX / Fast / Low CPU mode, tăng tốc thuyền, xóa sương mù, **Rain Fruits**, Full Bright, chỉnh Day/Night, **Walk on Water** |

> 📊 *Đếm thực tế từ mã nguồn:* **233 toggle · 105 button · 26 dropdown · 6 slider · 46 paragraph trạng thái · 15 tab.**

---

## 🎨 Giao diện

PT HUB đi kèm **engine UI tự xây (codename: NEO UI)** kiểu Maru — glassmorphism, neon, bo góc mềm, gradient và hiệu ứng shine:

- 🪟 **Cửa sổ kéo-thả** với sidebar icon, scroll mượt
- 🌈 **5 theme có sẵn:** Neonblue · Emerald Dark · Sunset · SlateStatic · SlateAnimated
- ✨ Hiệu ứng hover, click, toggle trượt, dropdown outside-window
- 🔔 Thông báo toast tích hợp (gọi `Window:Notify{...}`)
- 📱 Hoàn toàn responsive, có nút nổi cho mobile
- ⌨️ **Keybind thu nhỏ:** `Left Ctrl`
- 💾 Lưu cấu hình vào `PT HUB/settings/` và tự động autoload khi rejoin

> UI engine tự chứa — **KHÔNG gọi `loadstring` tới thư viện UI bên ngoài** (Fluent, Rayfield, Orion, Linoria…) nên vẫn chạy ổn trên executor chặn HTTP hoặc chặn thư viện lạ.

---

## 💾 Lưu cấu hình

Script tự quản lý một config tên **`PT HUB Config`**:

- Tạo file ngay lần chạy đầu tiên
- Sau khi bạn đổi **bất kỳ** toggle/slider/dropdown nào, config được tự động lưu lại sau ~2 giây
- Có một vòng lặp "safety net" lưu mỗi 20 giây
- Khi rejoin, mọi tùy chọn (kể cả Auto Farm) sẽ quay lại đúng trạng thái cũ

Ngoài ra thiết lập cấp thấp (âm thanh, theme, vị trí cửa sổ…) được lưu tại:

```
PT HUB/Settings.json
```

Toàn bộ thao tác file đều bọc `pcall` — nếu executor không hỗ trợ `writefile`/`readfile`/`makefolder`, script vẫn chạy bình thường, chỉ mất tính năng lưu.

---

## 🧠 Những fix kỹ thuật đáng chú ý

Khác với nhiều script Blox Fruits khác, PT HUB được vá kỹ cho các lỗi kinh điển:

- ✅ **Chờ Character/Data/Enemies với timeout** — không còn lỗi `attempt to index nil with 'HumanoidRootPart'` khi inject lúc vừa chết hoặc đang streaming.
- ✅ **Cập nhật `Root` sau mỗi lần respawn** — tele/farm không bị "kẹt" ở phần cũ.
- ✅ **`SafeInventory()`** — chống lỗi `missing argument #1 to 'pairs' (table expected)` khi server rate-limit remote `getInventory`.
- ✅ **Auto Store Fruit bản Blox Fruits mới** — nhận diện trái qua `EatRemote` + `ToolTip` + tên, chuẩn hóa key `"Name-Name"`, cooldown 3 giây/trái để không bị rate-limit.
- ✅ **Anti-spam hooks** — tắt tiếng `error`/`warn`, ẩn hiệu ứng Death + NPC Guide, làm Rocks/Foam trong suốt thay vì destroy (tránh spam `X is not a valid member of Part Foam;`).
- ✅ **Chờ UI với deadline 20s** — không treo vĩnh viễn trên Delta khi game load chậm.
- ✅ **Truy cập `ReplicatedStorage.Modules.Net` qua `WaitForChild` có timeout** — không crash khi module chưa replicate xong.
- ✅ **Tránh giới hạn 200 local variables của Luau** — các state dùng chung gắn vào `_G.PT_*`, file không bị từ chối compile trên executor yếu.

---

## 🎮 Điều khiển nhanh

| Thao tác | Tác dụng |
|---|---|
| `Left Ctrl` | Ẩn/hiện menu |
| Nút tròn nổi (mobile) | Ẩn/hiện menu |
| Kéo tiêu đề cửa sổ | Di chuyển menu |
| Bấm icon sidebar | Chuyển tab |
| Thanh search trong tab Teleport | Lọc NPC |

---

## 🧩 Tương thích

| Executor | Trạng thái |
|---|---|
| **Delta** (Android/PC) | ✅ Hỗ trợ chính |
| **Solara** | ✅ Hỗ trợ chính |
| **Xeno** | ✅ Hỗ trợ chính |
| Wave / Hydrogen / Fluxus / Arceus X / Codex / MacSploit | ✅ Chạy tốt |
| Executor không hỗ trợ `writefile` | ⚠️ Chạy được nhưng không lưu cấu hình |
| Executor không hỗ trợ `hookfunction` | ⚠️ Mất tính năng anti-spam VFX/error |

Script được thiết kế **defensive**: mọi API đặc thù (`hookfunction`, `writefile`, `makefolder`, `getgenv`, `VirtualInputManager`…) đều được kiểm tra trước khi gọi, nên thiếu hàm không làm chết script.

> ⚠️ Blox Fruits cập nhật hàng tuần. Nếu một tính năng nào đó không hoạt động sau update mới của game, hãy tạo issue trên repo để PT vá.

---

## 📁 Cấu trúc repo

```
Pthubv2/
└── Scriptload.lua      # Toàn bộ script (~14,471 dòng)
```

Một file duy nhất. Không build step, không `require` ngoài, không package manager.

Bố cục bên trong `Scriptload.lua`:

| Dòng | Nội dung |
|---|---|
| 1–67 | Bootstrap services + chờ Character/Data/Enemies |
| 68–117 | `PT HUB Settings.json` persistence |
| 119–171 | Performance / anti-spam hooks, Full Bright, Auto Ken |
| 173–677 | Bảng tra cứu boss/material/mob theo Sea, hàm chiến đấu, teleport, fruit utils, `SafeInventory` |
| 679–792 | Auto Store Fruit bản mới, Collect/Drop Fruit |
| 793–1668 | Các module farm, quest, item (giữa file) |
| 1669–2932 | **NEO UI engine** tự chứa + khởi tạo window và 15 tabs |
| 2934–3061 | GUI Settings tab (theme, animation, mobile button, media) |
| 3062–11530 | Toàn bộ tính năng trong 15 tabs |
| 11531–14388 | ESP, visual, travel, misc, FPS modules |
| 14389–14471 | Autoload cấu hình + Auto-save + thông báo khởi động |

---

## 🔧 Phát triển / đóng góp

1. Fork repo này
2. Sửa `Scriptload.lua`
3. Test trên ít nhất 2 executor (khuyến nghị Delta + Solara/Xeno)
4. Gửi Pull Request với mô tả rõ tính năng / fix

Vì file khá dài (~14k dòng), khi gửi PR hãy:

- Giữ phong cách code hiện tại (tiếng Anh cho logic, comment tiếng Việt khi giải thích bug)
- Bọc mọi call API executor bằng `pcall`
- Không hard-code `wait()` quá ngắn trong vòng lặp remote (dễ rate-limit)
- Không huỷ đối tượng mà game vẫn đọc từng frame (xem bài học `Foam;`)

---

## ❓ Câu hỏi thường gặp

**Menu không hiện sau khi execute?**
- Chờ 1–3 giây, script có vòng chờ UI game load tối đa 20s.
- Bấm `Left Ctrl` để ẩn/hiện (có thể bạn đã thu minimizer).
- Trên mobile hãy tìm nút tròn nổi đỏ.

**Bị "Script cannot be executed"?**
- Đảm bảo executor đã **attach** trước khi bấm execute.
- Cập nhật executor lên bản mới nhất.
- Một số executor chặn URL raw — hãy thử tải file `.lua` về và `loadfile`.

**Auto farm không chạy?**
- Kiểm tra đã chọn vũ khí trong dropdown `Select Weapon`.
- Kiểm tra `Safe Mode` và `Bring Mobs` đang bật.
- Mở tab Info, xem trạng thái đảo / boss có tương ứng Sea đang đứng không.

**Cấu hình không lưu?**
- Executor của bạn có thể không hỗ trợ `writefile`. Hãy dùng Delta/Solara/Xeno hoặc bất kỳ executor nào có workspace file.

**Có khoá / key không?**
- **Không.** Script miễn phí, không có key system, không có linkvertise, không có whitelist.

---

## ⚠️ Lưu ý

- Đây là script can thiệp vào client của [**Blox Fruits**](https://www.roblox.com/games/2753915549/). Việc dùng script bên thứ ba có thể đi ngược [Điều khoản dịch vụ của Roblox](https://en.help.roblox.com/hc/en-us/articles/115004647846).
- **Dùng tài khoản phụ (alt)** nếu bạn không muốn rủi ro bị ban trên tài khoản chính.
- Không sử dụng tính năng PvP/aimbot trong server public để tránh bị report.
- Tất cả logic chỉ chạy ở phía client bạn; PT không thu thập thông tin đăng nhập hay cookie.

---

## 👤 Tác giả

<div align="center">

**Made with ☕ and 🐍 by [Pt](https://github.com/hlpt411)**

Repo: [hlpt411/Pthubv2](https://github.com/hlpt411/Pthubv2)

*Cảm ơn tất cả ai đã dùng, báo lỗi và góp ý giúp PT HUB ngày một ổn định hơn.*

<img alt="PT HUB logo" width="120" src="https://www.roblox.com/headshot-thumbnail/image?userId=hlpt411&width=420&height=420&format=png" onerror="this.style.display='none'">

</div>

---

<div align="center">
<sub>🐍 PT HUB — IS BACK — created by PT</sub>
</div>
