q# bot.js – Lightweight JavaScript & CSS Loader with Dependency Management

**bot.js** is a small, dependency-free JavaScript loader that supports:
- Parallel and sequential loading
- Dependency management
- CSS and JS loading
- Module script support
- Alias definitions
- CDN fallback handling
- Cross-browser compatibility

> Originally developed by [Isaac Belly](https://github.com/m1a-bot)

---

## 📦 Features

- ✅ Load JS & CSS files in parallel or in order  
- ✅ Support for `type="module"` scripts  
- ✅ CDN fallback support via hash in URL  
- ✅ Dependency chaining  
- ✅ Custom aliases for grouped loading  
- ✅ Error handling hooks  

---

## 🚀 Usage Example

### Load a single script:

```html
<script src="bot.js"></script>
<script>
  ljs.load('https://code.jquery.com/jquery-3.7.1.min.js', function () {
    console.log('jQuery loaded!');
  });
</script>
