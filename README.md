<!DOCTYPE html>
<html lang="en">
    <html><head id="Head1"><meta http-equiv="Content-Type" content="text/html; charset=UTF-8"><meta http-equiv="X-UA-Compatible" content="IE=EDGE,chrome=1"><meta http-equiv="Page-Enter" content="blendTrans(Duration=0.1)"><meta http-equiv="Page-Exit" content="blendTrans(Duration=0.1)"><meta name="keywords" content="Steel &amp; Mines, Bihar Mining Corporation, Directorate of Mines"><meta name="description" content="Department of Steel &amp; Mines"><title>
        Department of Mines &amp; Geology, Government of Bihar
    </title>
    <link href="styles.css" type="text/css" rel="Stylesheet">
</head>
<body>
    <div id="wrapper">
        <form name="form1" method="post" action="" id="form1" enctype="multipart/form-data"></div>
            <div id="header">
                <div id="logo">
                    <img src="JIMMS_Logo.png" alt="Department of Mines &amp; Geology, Government of Bihar"></div>
                </div>
                
                        <div id="midbg">
                        <div id="midArea">
                            <table width="100%" border="0" cellspacing="0" cellpadding="0">
                                <tbody><tr>
                                    <td width="15">
                                    </td>
                                    <td height="492" valign="top">
                                        <div align="center" class="mandatory">
                                                <span id="Label1" style="font-family:Calibri;font-size:Medium;font-weight:bold;"></span>
                                            </div><div align="center" class="mandatory">
                                                <span id="lblMsg" style="font-family:Calibri;font-size:Medium;font-weight:bold;"></span>
                                            </div><table width="100%" border="0" cellspacing="0" cellpadding="0">
                                        
                                            <tbody><tr>
                                                <td>
                                                    <div class="title" id="title">
                                                        &nbsp;</div>
                                                    <div id="myTab">
                                                        <ul>
                                                            <li class="active"><a href="">View Pass Details </a></li>
                                                        </ul>
                                                    </div>
                                                </td>
                                            </tr>
                                            
                                            <tr>
                                                <td>
                                                    <div class="addTable">
                                                        <table width="80%" cellpadding="2" cellspacing="2">
                                                            <tbody><tr>
                                                                <td>
                                                                    Financial Year /
                                                                    वित्तीय वर्ष
                                                                </td>
                                                                <td>
                                                                    :
                                                                </td>
                                                                <td>
                                                                    <select name="ddlfinancialyear" id="ddlfinancialyear" style="width:167px;">
                    <option value="0">--Select All--</option>
                    <option value="2017-2018">2017-2018</option>
                    <option value="2018-2019">2018-2019</option>
                    <option value="2019-2020">2019-2020</option>
                    <option value="2020-2021">2020-2021</option>
                    <option value="2021-2022">2021-2022</option>
                    <option value="2022-2023">2022-2023</option>
                    <option value="2023-2024">2023-2024</option>
                    <option selected="selected" value="2024-2025">2024-2025</option>
                
                </select>
                                                                </td>
                                                                 <td>
                                                                    &nbsp;</td>
                                                            </tr>
                                                            <tr>
                                                                <td>
                                                                    Enter Challan Number
                                                                   चालान संख्या दर्ज करें.<span style="color: #FF0000;">*</span>
                                                                </td>
                                                                <td>
                                                                    : 
                                                                </td>
                                                                <td colspan="2" valign="middle">
                                                                    <input name="txtchallanno" type="text" maxlength="25" id="txtchallanno" style="width:150px;">
                                                                    
                                                                   
                                                                </td>
                                                                <td>
                                                                    &nbsp;
                                                                </td>
                                                            </tr>
                                                            <tr>
                                                                <td align="center" colspan="4" style="font-size: medium; font-weight: bold">
                                                                    OR</td>
                                                                <td>
                                                                    &nbsp;</td>
                                                            </tr>
                                                            <tr>
                                                                <td>
                                                                    Enter Vehicle No. / वाहन संख्या दर्ज करें.<span style="color: #FF0000;">*</span>
                                                                </td>
                                                                <td>
                                                                    : </td>
                                                                <td>
                                                                      <input name="txtVehicleNo" type="text" maxlength="14" id="txtVehicleNo" style="width:150px;" value="BR01GL4309">
                                                                      
                                                                        
                                                                    </td>
                                                                <td>
                                                                    <input type="text" name="btnsearch" value="Search" onclick="return CheckVal();" id="btnsearch" class="btnSubmit" style="width:100px;">
                                                                </td>
                                                                <td>
                                                                    &nbsp;</td>
                                                            </tr>
                                                            <tr>
                                                                <td>
                                                                    &nbsp;</td>
                                                                <td>
                                                                    &nbsp;</td>
                                                                <td>
                                                                      &nbsp;</td>
                                                                <td>
                                                                    &nbsp;</td>
                                                                <td>
                                                                    &nbsp;</td>
                                                            </tr>
                                                            </tbody></table>
                                                    </div>
                                                </td>
                                            </tr>
                                            
                                            <tr>
                                                <td align="left" valign="top">
                                                    <div align="left" style="color: Blue;">
                                                        Enter the challan no. / Vehicle No (Without space) to view the details
                                                    </div>
                                                    <div align="center" style="color: red;">
                                                        <span id="lblresult" style="font-size:11pt;font-weight:bold;"></span>
                                                    </div>
                                                    <div id="Panel1" style="color:Black;border-color:White;font-family:Verdana;font-size:11px;font-weight:bold;text-decoration:none;">
                    <fieldset>
                        <legend>
                            e-Pass Details
                        </legend>
                                                        <table border="0" cellpadding="3" cellspacing="8">
                                                            <tbody><tr>
                                                                <td>
                                                                    Challan No./चालान नंबर
                                                                </td>
                                                                <td width="2px">
                                                                    :
                                                                </td>
                                                                <td>
                                                                    <span id="lblchallanno" style="color:Blue;">564327856</span>
                                                                </td>
                                                                <td class="style1">
                                                                    &nbsp;
                                                                </td>
                                                                <td width="2px">
                                                                    &nbsp;
                                                                </td>
                                                                <td>
                                                                    &nbsp;
                                                                </td>
                                                            </tr>
                                                            <tr>
                                                                <td>
                                                                      UID No./ यूआईडी नंबर</td>
                                                                <td width="2px">
                                                                    :</td>
                                                                <td>
                                                                    <span id="lblUIDNo" style="color:Blue;">5643678587</span></td>
                                                                <td class="style1">
                                                                    &nbsp;</td>
                                                                <td width="2px">
                                                                    &nbsp;</td>
                                                                <td>
                                                                    &nbsp;</td>
                                                            </tr>
                                                            <tr>
                                                                <td>
                                                                    Challan Date / चालान की तिथि
                                                                </td>
                                                                <td width="2px">
                                                                    :
                                                                </td>
                                                                <td width="300px">
                                                                    <span id="lblchallandate" style="color:Blue;">13-Dec-2022 10:02 PM</span>
                                                                </td>
                                                                <td class="style1">
                                                                    &nbsp;
                                                                </td>
                                                                <td width="2px">
                                                                    &nbsp;
                                                                </td>
                                                                <td>
                                                                    &nbsp;
                                                                </td>
                                                            </tr>
                                                             <tr>
                                                                <td>
                                                                      Challan Validity/ चालान की वैधता</td>
                                                                <td width="2px">
                                                                    :</td>
                                                                <td>
                                                                    <span id="lblChallanValidity" style="color:Red;font-size:Medium;font-weight:bold;">13-Dec-2022 02:02 AM</span></td>
                                                                <td class="style1">
                                                                    &nbsp;</td>
                                                                <td width="2px">
                                                                    &nbsp;</td>
                                                                <td>
                                                                    &nbsp;</td>
                                                            </tr>
                                                            <tr>
                                                                <td>
                                                                    Consigner Name / कंसाइनर का नाम
                                                                </td>
                                                                <td width="10">
                                                                    :
                                                                </td>
                                                                <td>
                                                                    <span id="lblconsignername" style="color:Blue;">mukesh</span>
                                                                </td>
                                                                <td class="style1">
                                                                    &nbsp;
                                                                </td>
                                                                <td>
                                                                    &nbsp;
                                                                </td>
                                                                <td>
                                                                    &nbsp;
                                                                </td>
                                                            </tr>
                                                            <tr>
                                                                <td>
                                                                    Challan Generate from / चालान से उत्पन्न
                                                                </td>
                                                                <td>
                                                                    :
                                                                </td>
                                                                <td>
                                                                    <span id="lbluser" style="color:Blue;">web</span>
                                                                </td>
                                                                <td class="style1">
                                                                    &nbsp;
                                                                </td>
                                                                <td width="10">
                                                                    &nbsp;
                                                                </td>
                                                                <td>
                                                                    &nbsp;
                                                                </td>
                                                            </tr>
                                                            <tr>
                                                                <td>
                                                                    Location / स्थान
                                                                </td>
                                                                <td>
                                                                    :
                                                                </td>
                                                                <td>
                                                                    <span id="lbllocation" style="color:Blue;">patna</span>
                                                                </td>
                                                                <td class="style1">
                                                                </td>
                                                                <td>
                                                                    &nbsp;
                                                                </td>
                                                                <td>
                                                                </td>
                                                            </tr>
                                                            <tr>
                                                                <td>
                                                                    Destination / गंतव्य
                                                                </td>
                                                                <td>
                                                                    :
                                                                </td>
                                                                <td>
                                                                    <span id="lbldestination" style="color:Blue;">arwal</span>
                                                                </td>
                                                                <td class="style1">
                                                                    &nbsp;
                                                                </td>
                                                                <td>
                                                                    &nbsp;
                                                                </td>
                                                                <td>
                                                                    &nbsp;
                                                                </td>
                                                            </tr>
                                                             <tr>
                                                                <td>
                                                                   Vehicle Type / वाहन का प्रकार
                                                                </td>
                                                                <td>
                                                                    :
                                                                </td>
                                                                <td>
                                                                    <span id="lblVehicleType" style="color:Blue;">TRACTOR</span>
                                                                </td>
                                                                <td class="style1">
                                                                    &nbsp;
                                                                </td>
                                                                <td>
                                                                    &nbsp;
                                                                </td>
                                                                <td>
                                                                    &nbsp;
                                                                </td>
                                                            </tr>
                                                            <tr>
                                                                <td>
                                                                    Vehicle No. / वाहन नंबर
                                                                </td>
                                                                <td>
                                                                    :
                                                                </td>
                                                                <td>
                                                                    <span id="lblvehicleno" style="color:Red;font-size:Medium;font-weight:bold;">BR01GL4309</span>
                                                                </td>
                                                                <td class="style1">
                                                                </td>
                                                                <td>
                                                                    &nbsp;
                                                                </td>
                                                                <td>
                                                                </td>
                                                            </tr>
                                                            <tr>
                                                                <td>
                                                                    Mineral Name / खनिज का नाम
                                                                </td>
                                                                <td>
                                                                    :
                                                                </td>
                                                                <td>
                                                                    <span id="lblmineralname" style="color:Blue;">TIRUPATI</span>
                                                                </td>
                                                                <td class="style1">
                                                                    &nbsp;
                                                                </td>
                                                                <td>
                                                                    &nbsp;
                                                                </td>
                                                                <td>
                                                                    &nbsp;
                                                                </td>
                                                            </tr>
                                                            <tr>
                                                                <td>
                                                                    Quantity / मात्रा<span id="lblunit"></span>
                                                                </td>
                                                                <td>
                                                                    :
                                                                </td>
                                                                <td>
                                                                    <span id="lblquantity" style="color:Blue;">4.000</span>
                                                                </td>
                                                                <td class="style1">
                                                                    &nbsp;
                                                                </td>
                                                                <td>
                                                                    &nbsp;
                                                                </td>
                                                                <td>
                                                                    &nbsp;
                                                                </td>
                                                            </tr>
                                                            <tr>
                                                                <td>
                                                                    Consignee Name / प्राप्तकर्ता का नाम
                                                                </td>
                                                                <td>
                                                                    :
                                                                </td>
                                                                <td>
                                                                    <span id="lblconsigneename" style="color:Blue;">AMAN</span>
                                                                </td>
                                                                <td class="style1">
                                                                    &nbsp;
                                                                </td>
                                                                <td>
                                                                    &nbsp;
                                                                </td>
                                                                <td>
                                                                    &nbsp;
                                                                </td>
                                                            </tr>
                                                        </tbody></table>
                                                    
                    </fieldset>
                </div>
                                                </td>
                                            </tr>
                                        </tbody></table>
                                        <div>
                                            <input type="hidden" name="hndid" id="hndid" value="0">
                                        </div>
                                    </td>
                                </tr>
                            </tbody></table>
                        </div>
                    </div>
    
</body>
</html>
