1、GET在浏览器回退时是无害的，而POST会再次提交请求。 
2、GET产生的URL地址可以被Bookmark，而POST不可以。 
3、GET请求会被浏览器主动cache，而POST不会，除非手动设置。 
4、GET请求的参数会完整的被保存在历史记录里，POST不会。 
5、GET请求参数放在URL中，POST放在request body中。 
6、GET请求只能进行url编码，POST请求支持多种编码方式。 
7、对于参数类型，GET只接受ASCII字符，而POST没有限制。 
8、GET请求在URL中传递的参数是有长度限制的，而POST没有。 
9、GET比POST更不安全，因为参数直接暴露在URL中，所以不能传递敏感信息。