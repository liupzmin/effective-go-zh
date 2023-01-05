# effective-go-zh

> 希望能给 Go 后学带来更多有意义的内容

[effective go 中文版](https://github.com/liupzmin/effective-go-zh) 是我个人的文档轮子。为了帮助需要的人准确理解原文，特采纳中英双语格式，目前翻译初稿已经完成。

互联网上已有 `effective go ` 的中文版，甚至还不止一版，那为什么还要再造这个轮子呢？首先，我个人的初衷是为了锻炼自己的英文理解与翻译水平，同时也能磨砺中文的语言组织能力，更是为了把 go 语言的基础夯实。

其次，我初次读英文原文时，碰到有疑问的地方在中文版里往往得不到想要的答案，后来通过自己思考也解决了一些疑惑，有些问题是出自翻译的问题，比如最后一章有一句话：*The program here provides a nicer interface to one form of data: given a short piece of text, it calls on the chart server to produce a QR code, a matrix of boxes that encode the text.*

冒号之后的内容姑且不论，它是对 `a nicer interface` 的详细阐述。我们看前半句中的 `one form of data` 到底指什么？从字面意思看，或者由翻译软件翻译的话意思应该是：**一种数据类别**。我所见的两个翻译版本分别翻译成了 **一种数据格式** 和 **某种形式的数据**，可见就是照字面翻译，只是为了语句通顺问题，各自进行了调整。但即便是进行了调整，整个句子依然说不通，**此程序为一种数据格式提供了更好的的接口** 其意几何呢？

其实，下文中文档便给出了详细代码，html 的代码中有一个输入表单。我们知道 form 不仅有**形式、类别、种类**的意思，还具有**表格**的意思，并且在前端领域我们习惯于术语**表单**。所以此处分明是**一个数据的表单**之意！再者说，form 之前使用了数量词 `one` 而非定冠词 `a` ，我认为这是另一条佐证，这句话的本意是：**本程序为表单数据提供了更加友好的接口**。

除翻译问题外，春秋笔法，微言大义似乎也能造成困扰。`effective go` 虽为入门级必读资料，其内容算不上艰深，然而某些细微之处，于新手而言并不见得就能轻易领会，所以我在某些地方也注释了自己的心得。这看起来颇有几分古人注书的感觉，只不过我注的内容未必都对，所注条目也不甚多，但总归是自己花了精力的所思所想，相必对有些人有用也未可知，因此闲暇之余，又翻译了一版，很期待各位能够给予斧正。

因初稿未经校对，其中定有不少讹误疏漏之处，希望所有有兴趣的伙伴都能参与进来，不论是书写还是理解上的问题，都欢迎提交 `issue` 或者 `pr`，我定我会及时处理。

1. [介绍](https://github.com/liupzmin/effective-go-zh/blob/main/01.Introduction.md)
2. [格式化](https://github.com/liupzmin/effective-go-zh/blob/main/02.Formatting.md)
3. [注释](https://github.com/liupzmin/effective-go-zh/blob/main/03.Commentary.md)
4. [命名](https://github.com/liupzmin/effective-go-zh/blob/main/04.Names.md)
5. [分号](https://github.com/liupzmin/effective-go-zh/blob/main/05.Semicolons.md)
6. [控制结构](https://github.com/liupzmin/effective-go-zh/blob/main/06.ControlStructures.md)
6. [函数](https://github.com/liupzmin/effective-go-zh/blob/main/07.Functions.md)
6. [数据](https://github.com/liupzmin/effective-go-zh/blob/main/08.Data.md)
6. [初始化](https://github.com/liupzmin/effective-go-zh/blob/main/09.Initialization.md)
10. [方法](https://github.com/liupzmin/effective-go-zh/blob/main/10.Methods.md)
11. [接口和其它类型](https://github.com/liupzmin/effective-go-zh/blob/main/11.Interfaces-and-other-types.md)
12. [空白标识符](https://github.com/liupzmin/effective-go-zh/blob/main/12.The-blank-identifier.md)
13. [内嵌](https://github.com/liupzmin/effective-go-zh/blob/main/13.Embedding.md)
14. [并发](https://github.com/liupzmin/effective-go-zh/blob/main/14.Concurrency.md)
15. [错误](https://github.com/liupzmin/effective-go-zh/blob/main/15.Errors.md)
16. [一个 web 服务](https://github.com/liupzmin/effective-go-zh/blob/main/16.A-WebServer.md)
