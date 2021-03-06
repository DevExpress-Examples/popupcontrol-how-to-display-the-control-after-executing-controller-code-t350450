<!-- default file list -->
*Files to look at*:

* [HomeController.cs](./CS/Controllers/HomeController.cs) (VB: [HomeController.vb](./VB/Controllers/HomeController.vb))
* [AfterAsyncAjaxFormSubmit.cshtml](./CS/Views/Home/AfterAsyncAjaxFormSubmit.cshtml)
* [AfterJQueryAjax.cshtml](./CS/Views/Home/AfterJQueryAjax.cshtml)
* [AfterSyncFormSubmit.cshtml](./CS/Views/Home/AfterSyncFormSubmit.cshtml)
* [Index.cshtml](./CS/Views/Home/Index.cshtml)
* [OnLoad.cshtml](./CS/Views/Home/OnLoad.cshtml)
<!-- default file list end -->
# PopupControl - How to display the control after executing controller code
<!-- run online -->
**[[Run Online]](https://codecentral.devexpress.com/t350450/)**
<!-- run online end -->


This example illustrates several approaches to display the <a href="https://documentation.devexpress.com/#AspNet/CustomDocument9006">PopupControl</a> extension after performing server-side processing. In the simplest scenario we use the <a href="https://documentation.devexpress.com/#AspNet/DevExpressWebMvcPopupControlSettingsBase_ShowOnPageLoadtopic">PopupControlSettingsBase.ShowOnPageLoad</a> option to display the popup control initially. Note that we can pass any dynamic settings or content for the popup control through the ViewData dictionary. To show the popup control on the client side, we can call the <a href="https://documentation.devexpress.com/#AspNet/DevExpressWebScriptsASPxClientPopupControlBase_Showtopic(ZgszxA)">ASPxClientPopupControlBase.Show()</a> method. In addition we can use the <a href="https://documentation.devexpress.com/#AspNet/DevExpressWebScriptsASPxClientPopupControlBase_SetContentHtmltopic">ASPxClientPopupControlBase.SetContentHtml</a> method to modify popup content on the client side.<br><br>Finally, there is a scenario when the popup control should be displayed after a callback of some other extension. Please review the <a href="https://www.devexpress.com/Support/Center/p/T159638">T159638 - GridView - How to show a message after CRUD operations</a> code example, where we have illustrated how this can be implemented.<br><br><strong>See also:</strong><br><a href="https://www.devexpress.com/Support/Center/p/T303557">How to make PopupControl stay open after submitting a form using Ajax.BeginForm</a>

<br/>


