# 🖼️ 作業十：打造專屬的圖像生成 Web App

使用 **`majicMIX_realistic_v7`** 模型，結合漫畫風提示詞，建立一個能輸出高品質圖像的生成式應用。

---

## 🧠 模型名稱

`majicMIX_realistic_v7`

> 擅長生成融合寫實與漫畫風格的圖像，適用於角色設計與敘事插畫。

---

## 🚀 執行範例
Prompt:抑鬱女子

![alt text](圖片/image.png)

Prompt:紋身女子

![alt text](圖片/image-1.png)
---

## ✨ 提示詞增強設定（Positive Prompt）

```python
default_enhance = (
    "highly detailed, Japanese manga style, realistic manga shading, "
    "sharp linework, hand-drawn aesthetic, moody atmosphere, "
    "dramatic contrast, mature tone, seinen style, "
    "intricate character design, textured background, expressive eyes, "
    "inked outlines, storytelling composition"
)
```

📌 說明：
這些提示詞能夠引導模型生成具有日系漫畫氛圍、細膩筆觸、具敘事感的圖像，特別適合描繪人物、情境場景與故事場面。

---

## ❌ 避免提示詞設定（Negative Prompt）

```python
default_negative = (
    "blurry, low detail, distorted face, off-model, messy linework, "
    "inconsistent anatomy, low resolution, bad proportions, "
    "cartoonish style, simplified shading, western comic style"
)
```

📌 說明：
這些詞彙會幫助排除常見的圖像生成問題，如失真、低解析、人物變形或風格偏差等。