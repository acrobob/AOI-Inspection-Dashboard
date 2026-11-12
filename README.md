# AOI 檢測看板 Mockup / AOI Inspection Dashboard Mockup

以 Maker Ray AOI 檢測結果為資料來源的看板示意（全部為示意資料）。

- 線體 CD101–CD104、白班 / 夜班、機種 MDL-A100（主板）/ MDL-B210（子板）篩選
- KPI：生產板數、不良率（焊點）、DPU、AOI 誤判率、複判執行率
- 線別 / 日期 DPU 對比：可切換 X 軸、勾選瑕疵類型（Bridge / No Pin / Pin High / Missing）與瑕疵層別
- 瑕疵元件與位置：依 AOI「Whole Board Component Infos」格式，位號 Pareto（真不良 / 誤判、拼板 #1/#2、5 種瑕疵）＋位號明細
- 載具（Solder Pallet）版本 × DPU、複判狀況、單板明細與不良圖片（預設載入 / 點擊取得）
- 板階 FPYR 分頁：AOI 直通率 / 複判後 FPYR 趨勢、依線體表、板子不良主因（以 DPU 依 Poisson 推算，與 DPU 一致）
- 介紹分頁：看板六大特色（跨廠/線/站/機種、不干擾機台、DPU 篩選與層別、串接載具資訊、瑕疵影像速查、資料雲端化）
- English（預設）/ ไทย / 中文 切換

單一 `index.html`，無需建置，直接以 GitHub Pages 發佈。
