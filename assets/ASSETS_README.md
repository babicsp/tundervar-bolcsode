# Assets Needed

## Images to Download

### 1. Logo Image
- **Filename:** `logo.png`
- **Source URL:** https://static.wixstatic.com/media/193324_d6fc4fcbf5584b49b90580f42f8de5e1~mv2.png/v1/fill/w_427,h_525,al_c,q_85,usm_0.66_1.00_0.01,enc_avif,quality_auto/193324_d6fc4fcbf5584b49b90580f42f8de5e1~mv2.png
- **Location:** `assets/images/logo.png`
- **Description:** Tündérvár bölcsőde logo

### 2. Pricing Table Image
- **Filename:** `pricing.png`
- **Source URL:** https://static.wixstatic.com/media/193324_bb2242c21ac641e387729526f0be4453~mv2.png/v1/fill/w_896,h_358,al_c,q_85,usm_0.66_1.00_0.01,enc_avif,quality_auto/193324_bb2242c21ac641e387729526f0be4453~mv2.png
- **Location:** `assets/images/pricing.png`
- **Description:** Pricing table showing fees

### 3. Gallery Images
- **Location:** `assets/images/gallery/`
- **Description:** Additional photos of the nursery (to be provided by client)

## Instructions

To download the images, you can use:

```powershell
# Download logo
Invoke-WebRequest -Uri "https://static.wixstatic.com/media/193324_d6fc4fcbf5584b49b90580f42f8de5e1~mv2.png" -OutFile "assets\images\logo.png"

# Download pricing image
Invoke-WebRequest -Uri "https://static.wixstatic.com/media/193324_bb2242c21ac641e387729526f0be4453~mv2.png" -OutFile "assets\images\pricing.png"
```

## Directory Structure

```
assets/
  images/
    logo.png
    pricing.png
    gallery/
      (future gallery images)
```
