# Useful Code Snippets
Just JS, PHP &amp; MySQL Snippets I Find Useful

## Javascript
#### Google Analytics
This snipped was one I found when pulling in Analytics JS into a blade.php layout then needing to call a Analytics function from a VueJS file
```
<script>
window['GoogleAnalyticsObject'] = 'ga';
window['ga'] = window['ga'] || function() {
    (window['ga'].q = window['ga'].q || []).push(arguments)
};
</script>
```
This allows you to reference it as `window.ga()` from inside a VueJS component.
