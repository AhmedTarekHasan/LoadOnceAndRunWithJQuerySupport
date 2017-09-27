# Load Once And Run With JQuery Support
### How To Make Sure jQuery Is Loaded And Only Once

<br/>

While working with Sharepoint you will notice that adding jQuery to the main masterpage is not a good idea cause sometimes and with some jQuery versions problems happen just after adding jQuery even without using it. May be some of you encountered this problem or not but at least it happened to me and some other colleagues.

<br/>

So, the first lesson here is, don't add jQuery on every page except when you really need it.

<br/>

Also, when working with webparts, you may be using jQuery on more than one webpart, so you need to make sure that jQuery is added to whatever page including one of these webparts. Any page may include one or multiple of these webparts, so you can't depend on making only one of them responsible for adding jQuery to the page cause in case of absence of this webpart any jQuery code will fail.

<br/>

[This article](http://developmentsimplyput.blogspot.com/2012/12/how-make-sure-jquery-is-loaded-and-only.html) provides some valuable info regarding this topic.

<br/>

## Related Links:
* [Development Simply Put Blog Post](http://developmentsimplyput.blogspot.com/2012/12/how-make-sure-jquery-is-loaded-and-only.html)

<br/>

## Authors:
* [Ahmed Tarek Hasan](https://linkedin.com/in/atarekhasan)
