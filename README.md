1. <kbd>git clone https://github.com/joltmode/laravel-mix-vue-style-module.git</kbd>
2. <kbd>npm install</kbd>
3. <kbd>npm run dev</kbd>
4. <kbd>php -S localhost:20202 -t public</kbd>
5. open browser and navigate to <kbd>localhost:20202</kbd>
6. see how the **BLUE** message isn't actually blue
7. debug `<style>` nodes, see how it's not actually _css-module_'arized
8. if you have _Vue inspector_, also can notice how `Example` node contains `$style` property with no values
