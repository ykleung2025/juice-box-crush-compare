# 果汁盒凹入示範｜密封 vs 唔密封並排對比

小學科學教具：由第 1 步起左右分屏——左邊密封、右邊唔密封（縫隙／入氣口），對比盒內／盒外空氣壓力。

- Live：https://ykleung2025.github.io/juice-box-crush-compare/
- 單畫面版（姊妹）：https://ykleung2025.github.io/juice-box-crush/

小學科學逐步動畫：密封果汁盒用吸管吸走空氣之後，點解會凹；有縫隙／入氣口就唔會。

## 教學重點

當你用吸管吸走盒入面嘅果汁同空氣，而外面嘅空氣入唔到：

1. 盒入面氣體分子變少
2. 盒內空氣壓力下降
3. 盒外空氣壓力冇變，由外向內把紙盒壓凹

唔係「真空吸住」紙盒，係盒外空氣壓力推入來。如果飲管同紙盒之間縫隙好大，或者有入氣口，外面空氣即時入返補充，紙盒就唔會凹。

由第 1 步起，畫面永久左右並排：左邊＝密封，右邊＝唔密封（縫隙／入氣口已可見），方便對比；吸一下之後左凹、右唔凹。

## 點樣打開

- 本地：用瀏覽器打開 `index.html`（唔使安裝。檔案載入之後可以離線用，唔使網路，亦冇 API 金鑰）
- 網上課堂：<https://ykleung2025.github.io/juice-box-crush-compare/>

撳「下一步」「吸一下」「再吸一下」逐格睇。可以「上一步」翻查，「重設」或者最後嘅「再睇一次」返到開頭。

## 示範步驟

1. 兩個果汁盒 — 左密封、右唔密封（縫隙已可見）；兩邊未吸，氣壓都高
2. 兩邊氣壓都相同 — 向內、向外嘅力；密封同唔密封都相同
3. 吸走分子 — 左密封分子離開；右唔密封空氣由縫隙入返
4. 盒內空氣壓力下降 — 左降、右唔降
5. 認識盒外空氣壓力 — 盒外向內推嘅力；密封先至有壓力差
6. 紙盒凹入去 — 左凹、右唔凹；唔係真空吸住
7. 重溫一次 — 同時重溫密封同唔密封兩種情況

## GitHub Pages

如果上面條網址未開到，喺 GitHub 儲存庫開啟 Pages（`main` 分支、根目錄）：

1. 打開儲存庫 **Settings**
2. 左邊揀 **Pages**
3. **Build and deployment** → **Source** 揀 **Deploy from a branch**
4. **Branch** 揀 `main`，資料夾揀 `/ (root)`
5. 按 **Save**

幾分鐘後就會出現喺 <https://ykleung2025.github.io/juice-box-crush-compare/> 。

呢個網站係純靜態檔案（`index.html`、`styles.css`、`app.js`），唔使 build。

畫面用嘅字型係 [Noto Sans TC](https://fonts.google.com/noto/specimen/Noto+Sans+TC) 可變字重子集，授權見 `fonts/OFL.txt`。
