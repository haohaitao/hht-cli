<!--
 * @Description  : readme
 * @Author       : pacino
 * @Date         : 2021-09-01 17:47:34
 * @LastEditTime : 2021-09-22 15:37:20
 * @LastEditors  : pacino
-->
# hht-cli
A Vue scaffold.

# Installation
```
npm install hht-cli -g
```

# Usage
Open your terminal and type `hht` or `hht -h` , you'll see the help infomation below:
```
  Usage: hht <command>


  Commands:

    add       Add a new template
    delete    Delete a template
    list      List all the templates
    init      Generate a new project

  Options:

    -h, --help     output usage information
    -V, --version  output the version number
```

> Note that if you are using `MacOS`, `sudo` was required while using commands `add` and `delete`.

# demo
 - hht list (Show all templates)
```
{
   'vue2': 'haohaitao/vue-easy-template#main',
   'mobile-vue2': 'haohaitao/vue-h5-template#vue-h5-template',
   'uniapp': 'haohaitao/vue-uniapp-template#master'
}
```
- hht init vue2 test (Initialize a vue2 template named test)
- Wait for completion
# License
MIT.
