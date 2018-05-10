# confirmMessage
JqueryUI
var lselection
$("#divID").dialog({
  open:function(){
   lselection = $("#myselect").val() 
  },
  height: "auto",
  width:400,
  modal:true,
  title:title,
  buttons:{
    "Confirm":function(){
        $("#btn_Hidden").click();
  },
  "Cancel":function() {
    $(this).dialog("close");
  }
 }
});
