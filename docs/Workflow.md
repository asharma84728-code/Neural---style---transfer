1️⃣ User Input (Frontend)

The user interacts with a web interface built using HTML templates.

Uploads:
🖼️ Content Image (original image)
🎨 Style Image (artistic image)
Clicks “Generate” button

📁 File:

templates/index.html
2️⃣ Backend Request Handling

The Flask backend receives the uploaded images and processes them.

Images are saved in:
static/uploads/
Preprocessing is applied:
resizing
normalization
tensor conversion

📁 File:

app.py
3️⃣ Feature Extraction (Encoder Network)

A pretrained VGG network is used to extract deep features:

Content image → content features
Style image → style features

These features represent:

Content → structure & layout
Style → textures & colors

📁 Model:

vgg_normalised.pth
utils/models.py
