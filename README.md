<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Home Page - Secondary Annual Result 2024</title>
    <link href="/Content/css?v=2J7E-vLfnNmSRRpLwPu76env-nLzNJFsp2-40bJw_TE1" rel="stylesheet"/>

    <script src="/bundles/modernizr?v=inCVuEFe6J4Q07A0AcRsbJic_UE5MwpRMNGcOtk94TE1"></script>

</head>
<body class="skin-josh">
    <header class="header">
        <nav class="navbar navbar-static-top" role="navigation">
            <div>
                <a href="#" class="navbar-btn sidebar-toggle" data-toggle="offcanvas" role="button">
                    <div class="responsive_nav"></div>
                </a>
                <div align="center">
                    <a runat="server">
                        <img src="/Img2/Header.jpg" alt="Logo" class="img-responsive" style="width:300px;height:75px;">
                    </a>
                </div>
            </div>
        </nav>
    </header>
    <div class="container body-content">
        


<script type="text/javascript">
    function checkform() {
        var _rlcd = document.getElementById("txtRoleCode").value;
        var _rlno = document.getElementById("txtrollno").value;
        if (_rlcd == "") { swal("Error!", "please enter Roll Code", "error"); return false; }
        else if (_rlno == "") { swal("Error!", "please enter Roll Number", "error"); return false; }
        else if (document.getElementById("actualResult").value != document.getElementById("result").value) { swal("Error!", "captcha not matched", "error"); return false; }
        else {
            document.getElementById("frmsearch").submit();
        }
    }
</script>
<style>
    table, th, td { border-collapse: collapse; }
        table.center { margin-left: auto; margin-right: auto; }
    #rcorners2 { border-radius: 25px; border: 2px solid #73AD21;  }

</style>
<script type="text/javascript">function allowOnlyNumber(evt) { var charCode = (evt.which) ? evt.which : event.keyCode; if (charCode > 31 && (charCode < 48 || charCode > 57)) { swal("Error!", "Please enter number value", "error"); return false; } }</script>
<script type="text/javascript" src="https://ajax.googleapis.com/ajax/libs/jquery/1.8.3/jquery.min.js"></script>
<script type="text/javascript">
    $(document).ready(function () {
        var a = (Math.ceil(Math.random() * 99)) + 1;
        var b = (Math.ceil(Math.random() * 9)) + 1;
        var queryText = a + "     +     " + b + "=";
        document.getElementById('queryString').innerHTML = queryText;
        var result = parseInt(a) + parseInt(b);
        document.getElementById('actualResult').value = result;
    });</script>
<link href="/Content/css1.css" rel="stylesheet" />
<!-- global js -->
<link rel="stylesheet" type="text/css" href="/Content/vendors/sweetalert/css/sweetalert.css" />
<script type="text/javascript" src="/Content/vendors/sweetalert/js/sweetalert.min.js"></script>
<script type="text/javascript" src="/Content/vendors/sweetalert/js/sweetalert-dev.js"></script>

<section class="page-section portfolio">
    <h3 class="text-center text-uppercase font-weight-bold text-danger">-: <u> ANNUAL SECONDARY SCHOOL EXAMINATION RESULT, 2024</u> :-</h3>
<form action="/" autocomplete="off" id="frmsearch" method="post">        <div class="row">
            <div class="col-md-1"></div>
            <div class="col-md-10" style="padding:5px;">
                <div class="row">
                    <div class="col-md-3">
                        <strong style="color: red"></strong>
                    </div>
                    <div class="col-md-9">
                        <input type="text" id="txtRoleCode" name="txtRoleCode" onkeypress="return allowOnlyNumber(event);" autocomplete="off" maxlength="5" class="form-control" autofocus="true" placeholder="Enter Roll code" />
                    </div>
                </div>
                <div class="row">
                    <div class="col-md-3">
                        <strong style="color: red"></strong>
                    </div>
                    <div class="col-md-9">
                        <input type="text" id="txtrollno" name="txtrollno" onkeypress="return allowOnlyNumber(event);" autocomplete="off" maxlength="7" class="form-control" placeholder="Enter Roll No" />
                    </div>
                </div>
                <div class="row">
                    <div class="col-md-3">
                        <strong style="color:red"></strong>
                    </div>
                    <div class="col-md-9">
                        <label id="queryString"></label><br />
                        <input type="text" value="" id="result" class="form-control" placeholder="Enter captcha" /><input type="hidden" id="actualResult" />
                    </div>
                </div>
                <div class="row">
                    <div class="col-md-12 text-center">
                        <a href="javascript:void(0)" onclick="checkform();" class="btn btn-danger">Search Result</a>
                        
                    </div>
                </div>
            </div>
            <div class="col-md-1"></div>
        </div>
</form></section>
        <hr />
    </div>

    <script src="/bundles/jquery?v=8Oos0avDZyPg-cbyVzvkIfERIE1DGSe3sRQdCSYrgEQ1"></script>

    <script src="/bundles/bootstrap?v=M4Nk6kIOwMFflsEKET0iPL9i5YBqbzMzvUOrd8gyCnw1"></script>

    
</body>
</html>
