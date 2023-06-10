# DESCRIPTION
- **Fix:** Miss/wrong-named icons has proper names now.<br>
- **Fix:** Bulk and Twotone styles showing correctly now.<br>
- **Known-issue:** Very few of the Bold and Bulk styles have small glitches, SVGs are fine but I think, converting them to icon-font causes this problem.<br>

## USAGE
1. Import the [iconsax.css](iconsax.css) file to your project.
```html
<link rel="stylesheet" href="path/to/iconsax-css-updated/iconsax.css">
```
2. Change classes to vary your icon styles.
```html
<span class="isax-cube-scan-3d"></span>        <!-- outline -->
<span class="isax-bold-cube-scan-3d"></span>   <!--  bold   -->
<span class="isax-broken-cube-scan-3d"></span> <!-- broken  -->
<span class="isax-2tone-cube-scan-3d">         <!-- twotone -->
  <span class="path1"></span>
  <span class="path2"></span>
</span>
<span class="isax-bulk-cube-scan-3d">          <!--  bulk   -->
  <span class="path1"></span>
  <span class="path2"></span>
  <span class="path3"></span>
  <span class="path4"></span>
  <span class="path5"></span>
</span>
```
***Note:*** **bulk** and **2tone** styles must have **path$** childs. Each icon may have different count of child. You need to check them from CSS file which contains that style. ( [twotone.css](variants/twotone/style.css) or [bulk.css](variants/bulk/style.css) )

### RECOMMENDATION
If you use only one icon style at a time, you shouldn't store other font files due to page loading speed. And it is recomended to make them minified.