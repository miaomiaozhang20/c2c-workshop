# Adding Member Photos

## Quick Start

1. Add square photos (recommended 300x300px or larger) to the `photos/` folder
2. Name them exactly as shown below
3. Uncomment the `<img>` line in `index.html` for each person
4. Delete or comment out the 👤 emoji line

## Photo Naming Convention

**Co-Leaders:**
- `amanda-pratt.jpg`
- `miaomiao-zhang.jpg`

**Founding Members:**
- `adrienne-baer.jpg`
- `cyrille-grumbach.jpg`
- `shuping-wu.jpg`
- `omar-olivarez.jpg`
- `haley-lepp.jpg`
- `eric-zhou.jpg`
- `roni-shen.jpg`
- `jodie-koh.jpg`

## How to Add a Photo

### Step 1: Add the photo file
Save the photo in the `photos/` folder with the correct name (e.g., `photos/amanda-pratt.jpg`)

### Step 2: Update the HTML
Find the person's card in `index.html` and change:

```html
<!-- BEFORE -->
<div class="person-photo">
    <!-- <img src="photos/amanda-pratt.jpg" alt="Amanda Pratt"> -->
    👤
</div>
```

To:

```html
<!-- AFTER -->
<div class="person-photo">
    <img src="photos/amanda-pratt.jpg" alt="Amanda Pratt">
</div>
```

### Step 3: Commit and push
```bash
git add photos/ index.html
git commit -m "Add photo for [Name]"
git push
```

## Photo Guidelines

- **Format:** JPG, PNG, or WebP
- **Size:** Square aspect ratio (1:1), at least 300x300px
- **File size:** Keep under 500KB for fast loading
- **Background:** Clean, professional background preferred
- **Lighting:** Well-lit, clear face
