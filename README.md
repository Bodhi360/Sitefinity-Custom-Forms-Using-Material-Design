# Sitefinity-Custom-Forms-Using-Material-Design
Sitefinity Custom Forms Using Material Design using visual studio


<%@ Control %>
<%@ Register Assembly="Telerik.Sitefinity" TagPrefix="sf" Namespace="Telerik.Sitefinity.Web.UI" %>


<%--<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml" >
<head>
    
<!-- Material Design Bootstrap -->
<link href="/Sitefinity/WebsiteTemplates/ZaageTemplate/App_Themes/Zaage/Global/css/mdb.min.css" rel="stylesheet" />
   
    <title></title>
    <style type="text/css">
        body
{
    font-family: 'Conv_NettoOT' !important;
}

    </style>
</head>
<body>
     <form>--%>

<%--<div class="sfFieldWrp">--%>
<div class="col-responsive">
    
    <div class="md-form">
        <i class="fa fa-minus prefix grey-text"></i>
        <asp:Label runat="server" ID="titleLabel" CssClass="sfTxtLbl" Text="title label" AssociatedControlID="TextBox1" />
    <asp:TextBox ID="TextBox1" CssClass="sfTxt" runat="server" />
    
        </div>
     <span style="visibility: hidden;">text</span>

    <sf:SitefinityLabel runat="server" ID="descriptionLabel" WrapperTagName="div" CssClass="sfDescription"/>
    <sf:SitefinityLabel runat="server" ID="exampleLabel" WrapperTagName="div" CssClass="sfExample"/>
<%--</div>--%>
    </div>


         <%-- </form>

<!-- MDB core JavaScript -->
<script type="text/javascript" src="https://cdnjs.cloudflare.com/ajax/libs/mdbootstrap/4.5.0/js/mdb.min.js"></script>
</body>
</html>--%>
