Handlebars的语法增强API

Handlebars的语法非常易用，但为了更快的开发视图代码，Clouda还额外提供了便捷的工具方法

foreach 
用于快速遍历一个对象或数组

用法示例：

    <p id="test-foreach-caseB">  
        {{#foreach customObj}}{{key}} : {{value}}{{/foreach}}
    </p>