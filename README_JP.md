# Syria Population Analysis（日本語）

🇬🇧 English version: [README.md](README.md)

Python、Rasterio、Folium、およびオープンソースの地理空間データを用いて作成した、
シリア全土、および各地域を対象とする人口解析およびラスタデータ処理のワークフロー集

### 05 人口密度マップ

WorldPop人口ラスタデータを用いた人口密度の可視化

**主な内容**

- WorldPop 2026人口ラスタ
- 人口密度の可視化
- ラスタデータの正規化
- カスタムカラーマップ
- Folium ImageOverlay

---

### 06 Windowed Reading マップ

RasterioのWindowed Readingを用いた効率的なラスタ処理

**主な内容**

- Windowed Readingによるラスタ抽出
- メモリ使用量の削減
- ラスタデータの部分可視化
- Folium ImageOverlay

---

### 07 Zonal Statistics マップ

ゾーン統計（Zonal Statistics）を用いた県（Governorate）別人口推計

**主な内容**

- 県（Governorate）ポリゴンの選択
- ラスタ・ベクタ解析
- 人口集計
- 代表点の生成
- 比例シンボルマップ

---

### 08 Idleb Population Mask マップ

イドリブ県を対象とした人口ラスタデータの抽出

**主な内容**

- ポリゴンマスク
- GeoTIFF生成
- 対数変換（Log Transformation）
- ラスタデータの正規化
- ImageOverlayによる可視化

---

### 14 Raster Resample

Rasterioのリサンプリング手法を用いたラスタデータのダウンサンプリング

**主な内容**

- WorldPop人口ラスタ
- ラスタリサンプリング
- 双一次補間（Bilinear Interpolation）
- ラスタサイズの削減
- Folium ImageOverlay

---

### 15 Raster Resample Half

解像度を低減したGeoTIFFの最適化

**主な内容**

- Rasterio Average Resampling
- 解像度の低減
- GeoTIFFの最適化
- Transformの再計算
- 軽量ラスタの生成

---

### 16 Raster Reprojection

ラスタデータの座標参照系（CRS）の変換

**主な内容**

- CRSの確認
- EPSG:4326 → EPSG:3857変換
- ラスタデータの再投影
- Web Mercator対応
- GeoTIFF生成

---

### 19 Raster Normalization

Min-Max Normalizationを用いたデータ前処理

**主な内容**

- NumPy配列処理
- Min-Max Normalization
- 値のスケーリング（0–1）
- ラスタ前処理ワークフロー
- データの標準化

---

## データソース

### 行政境界

- HDX OCHA
- Syrian Arab Republic – Subnational Administrative Boundaries

### 人口ラスタ

- WorldPop：Syrian Arab Republic 100m Population 2026

### ベースマップ

- CARTO Light No Labels
- CARTO Dark Matter
- Esri World Imagery
- Esri World Terrain Base

---

## 使用技術

- Python
- GeoPandas
- Rasterio
- NumPy
- Matplotlib
- Folium

---

## 習得・実装した技術

- ラスタデータの可視化
- ラスタデータの正規化
- Windowed Reading
- ラスタマスキング
- ゾーン統計（Zonal Statistics）
- GeoTIFF生成
- 対数変換（Log Transformation）
- ラスタリサンプリング
- ラスタデータの再投影
- CRS変換
- Min-Max Normalization
- ImageOverlayによる描画
- 比例シンボルマッピング
