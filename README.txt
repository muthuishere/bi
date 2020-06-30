<html dir="ltr" class="secure"><head>
    <title>BI launch pad</title>
    
    
    
    <script language="javascript">
        var isDebugModeOn = false;
        var notificationListRowUrl = '../../InfoView/common/appService.do?service=skinning&resource=img&img=img.notification.list.icon ';
        var doNotificationPolling = true;
		var closeString = 'Close';
    </script>
   
    <link rel="shortcut icon" href="../images/InfoView.ico" type="image/x-icon">

    <link rel="stylesheet" type="text/css" href="../../shared/yui/2.8.0/assets/skins/sam/container.css">


    <link rel="stylesheet" type="text/css" href="../../InfoView/css/skin/container-skin-extension.css">


    <link rel="stylesheet" type="text/css" href="../../shared/yui/2.8.0/assets/skins/sam/resize.css">


    <link rel="stylesheet" type="text/css" href="../../shared/yui/2.8.0/assets/skins/sam/layout.css">


    <link rel="stylesheet" type="text/css" href="../../shared/yui/2.8.0/assets/skins/sam/menu.css">


    <link rel="stylesheet" type="text/css" href="../../shared/yui/2.8.0/assets/skins/sam/button.css">


    <link rel="stylesheet" type="text/css" href="../../shared/yui/2.8.0/assets/skins/sam/autocomplete.css">


    <script type="text/javascript" src="../../shared/yui/2.8.0/yahoo/yahoo-min.js"></script>
<script type="text/javascript" src="../../shared/yui/2.8.0/stylesheet/stylesheet-min.js"></script>
<script type="text/javascript" src="../../shared/js/core/langDirection.js"></script>
<script type="text/javascript" src="../../shared/ure/js/common/bobj-min.js"></script>
<script type="text/javascript" src="../../shared/ure/js/common/GarbageBin.js"></script>
<script type="text/javascript" src="../../shared/yui/2.8.0/yahoo-dom-event/yahoo-dom-event.js"></script>
<script type="text/javascript" src="../../shared/yui/2.8.0/logger/logger-min.js"></script>


    
    <link rel="stylesheet" type="text/css" href="../../InfoView/common/appService.do?service=skinning&amp;resource=stylesheet&amp;dir=ltr">
    
    <link rel="stylesheet" type="text/css" href="../../PerformanceManagement/styles/CTabs.css">
<script type="text/javascript" src="../../PerformanceManagement/scripting/bobjui/dash/utils/accessibility.js"></script>

    
    <link rel="stylesheet" type="text/css" href="../../InfoView/css/listing_main.css">


    
    <style type="text/css">
        #bannerArea {
            background-color:   #FFFFFF;
            background-image:   url( ../../InfoView/common/appService.do?service=skinning&resource=img&img=img.banner.background );
            background-repeat:  repeat-x;
            height:             25px;
            padding-top:        20px;
        }
		
        /* tab icons */
        a.closeIcon {
            background-image: url( ../../InfoView/common/appService.do?service=skinning&resource=img&img=img.panel.close );
        }

        a.closeIcon:hover {
            background-image: url( ../../InfoView/common/appService.do?service=skinning&resource=img&img=img.panel.close.hover );
        }

        a.closeIcon:active {
            background-image: url( ../../InfoView/common/appService.do?service=skinning&resource=img&img=img.panel.close.depressed );
        }

        a.newWindowIcon {
            background-image: url( ../../InfoView/common/appService.do?service=skinning&resource=img&img=img.tabs.newWindow );
        }

        a.newWindowIcon:hover {
            background-image: url( ../../InfoView/common/appService.do?service=skinning&resource=img&img=img.tabs.newWindow.hover );
        }

        a.newWindowIcon:active {
            background-image: url( ../../InfoView/common/appService.do?service=skinning&resource=img&img=img.tabs.newWindow.depressed );
        }

        a.pinIcon {
            background-image: url( ../../InfoView/common/appService.do?service=skinning&resource=img&img=img.tabs.unpinned );
        }

        a.pinIcon:hover {
            background-image: url( ../../InfoView/common/appService.do?service=skinning&resource=img&img=img.tabs.unpinned.hover );
        }

        a.pinIcon:active {
            background-image: url( ../../InfoView/common/appService.do?service=skinning&resource=img&img=img.tabs.unpinned.depressed );
        }

        a.pinIcon.isPinned {
            background-image: url( ../../InfoView/common/appService.do?service=skinning&resource=img&img=img.tabs.pinned );
        }

        a.pinIcon.isPinned:hover {
            background-image: url( ../../InfoView/common/appService.do?service=skinning&resource=img&img=img.tabs.pinned.hover );
        }

        a.pinIcon.isPinned:active {
            background-image: url( ../../InfoView/common/appService.do?service=skinning&resource=img&img=img.tabs.pinned.depressed );
        }
    </style>

    <script type="text/javascript" src="../../InfoView/js/utils.js"></script>


    <script type="text/javascript" src="../../shared/js/caf/shared_caf_utils.js"></script>


    

    <script type="text/javascript">

    var PGDATA = {};

    // Get the InfoView prefix to the URL for supportability as the root context        
    var rootContext = '/portal/1603120824';

    PGDATA.appName = "BI launch pad";
    PGDATA.warName = "/InfoView";
    PGDATA.faviconPath = "../images/InfoView.ico";

    INFOVIEW.isNewWindow = false;
    if (INFOVIEW.isNewWindow) {
        var newWindowWorkspace = {
                actionParameters : {url : "null"},
                setTitle : function(title) {
                    document.title = title;
                }
        };
    }

    PGDATA.appServiceUrl = "/common/appService.do";

    INFOVIEW.productLocale = 'en';
    INFOVIEW.preferredViewingLocale = 'en_US';

    PGDATA.commonLoading = "Loading...";

    INFOVIEW.omitDocumentExplorerTab = null;
    INFOVIEW.omitHelpMenu = false;
    INFOVIEW.viewMode = '2';

    INFOVIEW.dialogContentContainerLabel = "Dialog Box Content";
    
    INFOVIEW.tooltips = {
        "newWindow":        "Open in a new window",
        "pin":              "Pin this tab",
        "unPin":            "Unpin this tab",
        "close":            "Close this tab",
        "closeDialog":      "Close this dialog box",
        "maximize":         "Maximize this dialog box",
        "restore":          "Restore this dialog box",
        "help":             "Help menu",
        "closeDetails":     "Close the details panel",
        "openDetails":      "Open the details panel",
        "closeButtonAlt":   "Close",
        "detailsAlert":     "The details panel is open"
    };

    INFOVIEW.userPrefParams = "pref=maxOpageUt%3D500%3BmaxOpageC%3D10%3Btz%3DAmerica%2FChicago%3BmUnit%3Dinch%3BshowFilters%3Dtrue%3BsmtpFrom%3Dtrue%3BpromptForUnsavedData%3Dtrue%3B";

    // store any serialized tabs for deserialization
    INFOVIEW.tabs = {};

    PGDATA.viewModePortal = '2';
    PGDATA.openDocFrameName = 'infoviewOpenDocFrame';
    PGDATA.mainNewWindowUrl = '/listing/main.do?service=/common/appService.do&appKind=InfoView&isNewWindow=true&newUrl=';
    PGDATA.rpContext = '../..';
    PGDATA.cafJsParams = 'bttoken=MDAwRGZgNT1TRj9VV2FHMWNpYmpBWjNWQ1dPUE43ODAEQ';
    PGDATA.openDocFrameParam = 'opendocTarget=infoviewOpenDocFrame';
    PGDATA.context = "..";
    PGDATA.objectKindParam = "objKind";
    PGDATA.viewModeSingle = '0';
    PGDATA.viewModeMultiple = '1';
    PGDATA.confirmMsg = "If you continue, unsaved changes will be lost. Do you want to continue?";
    PGDATA.toolTipClose = "Close this tab";
    PGDATA.objIdParam = "objIds";
    PGDATA.containerIdParam = "containerId";
    PGDATA.contextPath = '../../InfoView';

    INFOVIEW.appCache = {"prefsString":"pref=maxOpageUt%3D500%3BmaxOpageC%3D10%3Btz%3DAmerica%2FChicago%3BmUnit%3Dinch%3BshowFilters%3Dtrue%3BsmtpFrom%3Dtrue%3BpromptForUnsavedData%3Dtrue%3B&loc=en&pvl=en_US","aboutAction":{"name":"About","context":"../../PlatformServices","icon":"","id":4472,"type":"","url":"/jsp/About/about.faces?cafWebSesInit=true&bttoken=MDAwRGZgNT1TRj9VV2FHMWNpYmpBWjNWQ1dPUE43ODAEQ&bttoken=MDAwRGZgNT1TRj9VV2FHMWNpYmpBWjNWQ1dPUE43ODAEQ"},"promptForUnsavedData":false,"promptWhenCloseActions":[4579,6157672,4697,4809,4427],"listingAction":{"name":"Documents","context":"../../InfoViewAppActions","icon":"","id":4257,"type":"","url":"/jsp/InfoView_Listing/infoviewListing.faces?cafWebSesInit=true&bttoken=MDAwRGZgNT1TRj9VV2FHMWNpYmpBWjNWQ1dPUE43ODAEQ&bttoken=MDAwRGZgNT1TRj9VV2FHMWNpYmpBWjNWQ1dPUE43ODAEQ"},"invisibleActions":[4227,6157652,6157655,6157649,4626,4759,4259,4260,4261,4776,4526,4665,4026,4033,4162,4291,4675,4295,4296,4297,4051,4563,4691,4565,4699,4190,4830,4191,4449,4705,4068,4708,4069,4331,4332,4090],"locale":"en","autoNavActions":[4480,4741,1552861,4624,5969,4499,4755,4563,4501,4246,4502,4759,4444,4508,4640,4577,4578,4263,4782,4591,4401,4402,4595,4660,6157671,4287],"newWindowActions":[4480,4224,4741,4620,4621,4627,4252,4127,4640,4263,4520,4400,4401,4529,4402,4153,6157667,4287,4289,4676,1552850,1552863,1552861,1552859,4557,4560,5969,5971,4180,4053,5973,5975,5977,4443,5979,4444,4704,4065,4066,4323,4327,4328,4591,4471,4217,4730,4731,4095],"cafParameterString":"bttoken=MDAwRGZgNT1TRj9VV2FHMWNpYmpBWjNWQ1dPUE43ODAEQ","preferencesAction":{"name":"Preferences","context":"../../PlatformServices","icon":"","objId":"4419737","extraParam":"disablePrefLocale=false&supportMyGroups=false","id":4350,"type":"","url":"/jsp/Shared_ActionSet/actionset.faces?cafWebSesInit=true&bttoken=MDAwRGZgNT1TRj9VV2FHMWNpYmpBWjNWQ1dPUE43ODAEQ&bttoken=MDAwRGZgNT1TRj9VV2FHMWNpYmpBWjNWQ1dPUE43ODAEQ"},"helpAction":{"name":"Help","context":"../../PlatformServices","icon":"/images/help.gif","id":4443,"type":"Launch","url":"/jsp/Help/helpRedirect.faces?cafWebSesInit=true&bttoken=MDAwRGZgNT1TRj9VV2FHMWNpYmpBWjNWQ1dPUE43ODAEQ&bttoken=MDAwRGZgNT1TRj9VV2FHMWNpYmpBWjNWQ1dPUE43ODAEQ"},"openInTab":[4224,4480,4741,4620,4621,4627,4252,4508,4127,4640,4257,4263,4520,4400,4401,4529,4402,4153,4154,4287,4289,4676,1552850,1552863,1552861,1552859,4557,5969,5971,4180,4053,5973,5975,5977,5979,4444,4704,4066,4323,4328,4591,4086,4471,4217,4730,4731,4095],"cafParameters":["bttoken"],"alwaysNewWindowActions":[4595,4325,4086,4154,4443],"gotoAppActions":[{"name":"Crystal Reports for Enterprise","context":"../../CrystalReports","icon":"/images/rpt_create.png","id":4407,"type":"","url":"/jsp/CrystalReport_Create/create.faces?cafWebSesInit=true&bttoken=MDAwRGZgNT1TRj9VV2FHMWNpYmpBWjNWQ1dPUE43ODAEQ&bttoken=MDAwRGZgNT1TRj9VV2FHMWNpYmpBWjNWQ1dPUE43ODAEQ"},{"name":"Web Intelligence","context":"../../AnalyticalReporting","icon":"/images/WebI_16x16.png","id":4520,"type":"","url":"/WebiView.do?noDocument=true&cafWebSesInit=true&bttoken=MDAwRGZgNT1TRj9VV2FHMWNpYmpBWjNWQ1dPUE43ODAEQ&bttoken=MDAwRGZgNT1TRj9VV2FHMWNpYmpBWjNWQ1dPUE43ODAEQ"}],"actionsRequiringShim":[4401,4676,4053,1552850,1552863,1552861,1552859,4095],"prefsParameters":["pref","loc","pvl"],"actionsRequiringSearchContext":[],"actionSetNavigationActions":[6157662,4808,4809,4810,4817,4818,4499,4755,4819,4501,4246,4502,4697,4698,4636,4637,4829,4638,4577,4578,4579,4580,4583,4842,4782,4846,4783,4660,6157673,4661,6157672,4662,4663,4728,4792,4729,6157671,4348,4350],"detailsPanelAction":{"name":"Details","context":"../../PlatformServices","icon":"","id":4376,"type":"DetailsPanel","url":"/jsp/Shared_DetailsPanel/detailsPanel.faces?cafWebSesInit=true&bttoken=MDAwRGZgNT1TRj9VV2FHMWNpYmpBWjNWQ1dPUE43ODAEQ&bttoken=MDAwRGZgNT1TRj9VV2FHMWNpYmpBWjNWQ1dPUE43ODAEQ"}};

    function onBtnPrefsClick() {
        
            INFOVIEW.useGlobalDialogManager = true;
            var prefActionUrl = INFOVIEW.appCache.preferencesAction.context + INFOVIEW.appCache.preferencesAction.url;
            caf_callback_invokeAction(prefActionUrl, INFOVIEW.appCache.preferencesAction.id, INFOVIEW.appCache.preferencesAction.objId, "", INFOVIEW.appCache.preferencesAction.type, null, INFOVIEW.appCache.preferencesAction.extraParam, window, null);
        
    }
	
	callbackGetBTTOKEN2=function(){
	var token = 'MDAwRFZtUFNlQVhsZzJhXUFVOWhoYGVYQEhpSkoyPTAAN'
    return token;	
	}
	
	callbackGetBTToken =function(){
		var obj ='MDAwRGZgNT1TRj9VV2FHMWNpYmpBWjNWQ1dPUE43ODAEQ';
		return obj;
		}  
		
    PGDATA.dashboardErr = "The system is unable to initialize the Dashboard component";
    PGDATA.searchNoResults = "No results";
    PGDATA.searchSeeAllResults = "See all results...";
    PGDATA.prefsUpdateTitle = "Preferences Changed";
    PGDATA.prefsUpdateMessage = "Changes to some preferences will take effect after the page reloads.";

    PGDATA.appKindParam = 'appKind';
    PGDATA.userId = '4419737',
    PGDATA.homeTooltip = "Home";
    PGDATA.listing = "Documents";
    PGDATA.imageServiceUrl = "../../InfoView/common/appService.do?service=skinning&resource=img&img=";
    PGDATA.about = "About";

    PGDATA.errorTitle = "Error";
   
    
    </script>
    <!--  adding notification js and css files -->
    <script src="../js/jquery-1.8.3.js"></script>
   	<script type="text/javascript" src="../js/notification.js"></script>
    <link rel="stylesheet" type="text/css" href="../../InfoView/css/notification.css">


   
    <script type="text/javascript" src="../js/listing_main_a.js"></script><link rel="shortcut icon" type="image/x-icon" href="https://ibsbusint-system.fnfis.com/BOE4/BOE/portal/1603120824/InfoView../images/InfoView.ico">
	<script>
		function sendXmlHttpGet(Url, asyncFlag)
		 {
		    var xmlHttp;
		    try
		    {
			    // Firefox, Opera 8.0+, Safari
			    xmlHttp=new XMLHttpRequest();
		    }
		    catch (e)
		    {
		    // Internet Explorer
			    try
			      {
			      	xmlHttp=new ActiveXObject("Msxml2.XMLHTTP");
			      }
			    catch (e)
			      {
				      try
				        {
				        	xmlHttp=new ActiveXObject("Microsoft.XMLHTTP");
				        }
				      catch (e)
				        {
					        //alert("Your browser does not support AJAX!");
					        return false;
				        }
			      }
		    }
		    var async = true;
		    if (asyncFlag != "undefined" && asyncFlag != null)
		    {
		       async = asyncFlag;
		    } 
		    
		    xmlHttp.open("GET", Url, async);
		    xmlHttp.send();
		}
		    
	   function resetSession()
	   {
		   /*this method will reset session timeout to initial time 
   			whenever a refresh happens closeSession() sets the time out to 30 secs and this method resets back to old time
   			*/
	   		var randomNum = Math.round(Math.random() * 10000);
	   		sendXmlHttpGet('../../BIPCoreWeb/ResetSessionTime'+ '?rand=' + randomNum + '&appKind=' + appKind,true);
	   	
	   }
	   function closeSession()
	   {
		   /*this method will set session timeout to 30 secs;
   			this method is called in browser refresh and browser close. 
   			whenever a refresh happens this method sets the time out to 30 secs 
   			and resetSession method resets back to old time (20 mins)
   			*/
		   	var randomNum = Math.round(Math.random() * 10000);
		   	var loggedoff = logofflink;
   			logofflink=false;
		   	sendXmlHttpGet('../../BIPCoreWeb/TimeoutSession' + '?rand=' + randomNum+'&logofflink='+loggedoff + '&appKind=' + appKind,true);
	   	
	   }
	   
	   function onBodyLoad() {
	   		resetSession();
	   		onLoad();
	   } 
	</script>
</head>
<body onload="javascript:onBodyLoad()" onunload="closeSession()" onresize="resizePanel();" class="yui-skin-sam masked" style="overflow: hidden;"><iframe src="javascript:false;" tabindex="-1" class="yui-overlay-iframe" style="opacity: 0; position: absolute; border: none; margin: 0px; padding: 0px; display: block; width: 1306px; height: 566px; left: 31.15px; top: 69px; z-index: 2;" id="globaldlg_panel0_f"></iframe><div class="mask" id="globaldlg_panel0_mask" style="z-index: 2; width: 401px; height: 657px; display: block;">&nbsp;</div><span class="yui-resize-status"></span><div class="yui-panel-container focused" id="globaldlg_panel0_c" style="left: 34.15px; top: 72px; visibility: visible; z-index: 3;"><div id="globaldlg_panel0" class="yui-module yui-overlay yui-panel dialogPanel yui-resize" role="dialog" style="visibility: inherit; width: 1297.7px; height: 558.45px;"><div class="hd" id="yui-gen6" style="cursor: move;">Preferences – Anand Balakrishnan</div><div class="bd" style="height: 499px;"><iframe onload="DIALOG.dlg_onIframeLoad(0)" name="dlgContainer0" id="dlgContainer0" class="dlgContainer" src="../../InfoView/jsp/common/actionNavFrame.jsp?bttoken=MDAwRGZgNT1TRj9VV2FHMWNpYmpBWjNWQ1dPUE43ODAEQ&amp;url=..%2F..%2FPlatformServices%2Fjsp%2FShared_ActionSet%2Factionset.faces%3FcafWebSesInit%3Dtrue%26bttoken%3DMDAwRGZgNT1TRj9VV2FHMWNpYmpBWjNWQ1dPUE43ODAEQ%26bttoken%3DMDAwRGZgNT1TRj9VV2FHMWNpYmpBWjNWQ1dPUE43ODAEQ%26appKind%3DInfoView%26service%3D%252FInfoView%252Fcommon%252FappService.do%26loc%3Den%26pvl%3Den_US%26ctx%3Dstandalone%26actId%3D4350%26objIds%3D4419737%26containerId%3D%26pref%3DmaxOpageUt%253D500%253BmaxOpageC%253D10%253Btz%253DAmerica%252FChicago%253BmUnit%253Dinch%253BshowFilters%253Dtrue%253BsmtpFrom%253Dtrue%253BpromptForUnsavedData%253Dtrue%253B%26disablePrefLocale%3Dfalse%26supportMyGroups%3Dfalse" frameborder="0" width="100%" height="100%" title="Dialog Box Content"></iframe></div><div class="ft"></div><span id="globaldlg_panel0_help" class="icon help" title="Help menu" tabindex="0"></span><span id="globaldlg_panel0_maxrestore" class="icon maximize" title="Maximize this dialog box" tabindex="0"></span><span class="container-close" title="Close this dialog box" tabindex="0">&nbsp;</span><button style="position: absolute; left: -999px;"></button><div id="yui-gen7" class="yui-resize-handle yui-resize-handle-br"><div class="yui-resize-handle-inner-br"></div></div></div><div class="yui-resize-proxy" style="height: 0px; width: 0px;"></div></div><iframe id="_yuiResizeMonitor" title="Text Resize Monitor" role="presentation" tabindex="-1" style="position: absolute; visibility: visible; background-color: transparent; border-width: 0px; width: 2em; height: 2em; left: 0px; top: -23px;"></iframe>


<div>
    <div id="top">
    

    
        
        
        
            <div id="bannerArea" role="banner">
                <div id="bannerLogo" class="absolute" style="width: 300px;
                            height: 100px;
                            background-image: url(../../InfoView/common/appService.do?service=skinning&amp;resource=img&amp;img=img.banner.logo);
                            background-repeat: no-repeat;
                            background-color: transparent;
                            background-attachment: scroll;
                            background-position: 0 0;">
                 </div>
                 
                 <div id="bannerNotification" class="absolute bannerNotification" style="display: none;">
                 	<table>
                 		<tbody><tr>
                 			<td><div class="notificationBannerIconClass" style="background-image :url(../../InfoView/common/appService.do?service=skinning&amp;resource=img&amp;img=img.notification.icon);"></div></td>
                 			<td><div id="notificationMessage" class="notificationMessageClass" style="width: 0px;"></div></td>
                 			<td><div class="notificationDetailLinkClass"><a id="notificationDetailLink" href="#" onclick="initNotification();"></a></div></td>
                 			<td><div class="notificationBannerCloseBtn" style="background-image :url( ../../InfoView/common/appService.do?service=skinning&amp;resource=img&amp;img=img.notification.close);" title="Close" onclick="closeNotification();"></div></td>
                 		</tr>
                 	</tbody></table>
                 </div>

                <div id="bannerContent">
                    
                         
                             Welcome:
                             <span class="bannerUserName">
                                 Anand Balakrishnan
                             </span>                             
                             <span class="linkSeparator">|</span>
                         
                     
                            
                    
                        <span class="yui-button yui-menu-button headermenubutton" id="gotomenubutton"><span class="first-child"><button type="button" tabindex="0" title="Open the Applications menu" id="gotomenubutton-button" aria-haspopup="true" aria-owns="gotomenu">Applications</button></span></span>
                        <div id="gotomenu" class="headermenu yuimenu yui-module yui-overlay yui-button-menu yui-menu-button-menu yui-overlay-hidden" style="visibility: hidden; position: absolute; z-index: 1;" role="menu"><div class="bd"><ul class="first-of-type"><li class="yuimenuitem first-of-type" id="yui-gen2" groupindex="0" index="0"><a href="#" class="yuimenuitemlabel" role="menuitem" tabindex="0" style="background-image: url(&quot;../../CrystalReports/images/rpt_create.png&quot;); background-repeat: no-repeat; background-position: left center; margin-left: 4px;">Crystal Reports for Enterprise</a></li><li class="yuimenuitem" id="yui-gen3" groupindex="0" index="1"><a href="#" class="yuimenuitemlabel" role="menuitem" tabindex="-1" style="background-image: url(&quot;../../AnalyticalReporting/images/WebI_16x16.png&quot;); background-repeat: no-repeat; background-position: left center; margin-left: 4px;">Web Intelligence</a></li></ul></div></div>
                    

                    
                        <span class="yui-button yui-push-button headermenubutton linkbutton" id="prefsLink"><span class="first-child"><button type="button" tabindex="0" title="Set Preferences" id="prefsLink-button">Preferences</button></span></span>
                    

                    
                        
                            <span class="yui-button yui-menu-button headermenubutton" id="helpmenubutton"><span class="first-child"><button type="button" tabindex="0" title="Help menu" id="helpmenubutton-button" aria-haspopup="true" aria-owns="helpmenu">Help menu</button></span></span>
                            <div id="helpmenu" class="headermenu yuimenu yui-module yui-overlay yui-button-menu yui-menu-button-menu yui-overlay-hidden" style="visibility: hidden; position: absolute; z-index: 1;" role="menu"><div class="bd"><ul class="first-of-type"><li class="yuimenuitem first-of-type" id="yui-gen4" groupindex="0" index="0"><a href="#" class="yuimenuitemlabel" role="menuitem" tabindex="0" style="background-image: url(&quot;../../PlatformServices/images/help.gif&quot;); background-repeat: no-repeat; background-position: left center; margin-left: 4px;">Help</a></li><li class="yuimenuitem" id="yui-gen5" groupindex="0" index="1"><a href="#" class="yuimenuitemlabel" role="menuitem" tabindex="-1" style="background-image: url(&quot;../../InfoView/common/appService.do?service=skinning&amp;resource=img&amp;img=img.about&quot;); background-repeat: no-repeat; background-position: left center; margin-left: 4px;">About</a></li></ul></div></div>
                    
                            <span class="linkSeparator" style="padding-left: 0px">|</span>
                    
                            <span class="yui-button yui-push-button headermenubutton linkbutton" id="logoffLink"><span class="first-child"><button type="button" tabindex="0" title="Log off" id="logoffLink-button">Log off</button></span></span>
                        
                     
                </div>
                <div id="bannerSearchArea" class="absolute">
                    <div id="searchAutoCompleteDiv" role="search" style="width: 212px;">
                        <label for="infoviewSearchInput" class="offScreen">Search</label>
                        <input class="inputTextBox textInput yui-ac-input" type="text" id="infoviewSearchInput" style="margin: 0px; width: 200px;" autocomplete="off" role="combobox" aria-owns="infoViewSearchAutoCompleteList" aria-expanded="false" aria-autocomplete="list">
                        
                        <button id="searchButton" class="absolute" onclick="javscript:search();" type="button" title="Search"><img src="../../InfoView/common/appService.do?service=skinning&amp;resource=img&amp;img=img.search" alt="Search"></button>
                        
                    </div>
                </div>

            </div>

        
    

    <div id="InfoViewTabContainerLabel" class="offScreen">Tab bar</div>
    <div id="panelToolBarHolder" class="panelToolbar" role="navigation" aria-labelledby="InfoViewTabContainerLabel">
        <div id="InfoViewTabContainer">
        <div class="TabContainer infoviewTab topTab safari" id="id_1" style="overflow: hidden;"><div class="TabItem _SubTab tabItemHolder tabSliderButton" id="id_3" style="width: 21px; display: none;"><div class="TabLeft"></div><div class="TabContent TitleTabContainer"><a href="javascript:void(null);" onclick="return !1;" class="TabTitle" role="button" title="Scroll Left" style="width: auto;">&lt;</a></div><div class="TabRight"></div></div><div style="width: 329px;" class="tabSlider" role="tablist"><div class="hiddenOverflowContainer"><div id="id_2" class="hiddenTabContainer"><div class="TabItem _SubTab tabItemHolder Active" id="id_7" style="width: 43px;"><div class="bottomTopTab" style="overflow: hidden; width: 43px;"></div><div class="TabLeft"></div><div class="TabContent TitleTabContainer"><a href="javascript:void(null);" onclick="return !1;" class="TabTitle" role="tab" title="Home" style="width: auto;">Home</a></div><div class="TabRight"></div></div><div class="TabItem _SubTab tabItemHolder" id="id_8" style="width: 65px;"><div class="TabLeft"></div><div class="TabContent TitleTabContainer"><a href="javascript:void(null);" onclick="return !1;" class="TabTitle" role="tab" title="Documents" style="width: auto;">Documents</a></div><div class="TabRight"></div></div></div></div></div><div class="TabItem _SubTab tabItemHolder tabSliderButton" id="id_4" style="width: 21px; display: none;"><div class="TabLeft"></div><div class="TabContent TitleTabContainer"><a href="javascript:void(null);" onclick="return !1;" class="TabTitle" role="button" title="Scroll Right" style="width: auto;">&gt;</a></div><div class="TabRight"></div></div><div class="TabItem _SubTab tabItemHolder tabSliderButton" id="id_5" style="width: 22px; display: none;"><div class="TabLeft"></div><div class="TabContent TitleTabContainer"><a href="javascript:void(null);" onclick="return !1;" class="TabTitle" role="button" title="List All Tabs" aria-haspopup="true" id="sliderMenuId" style="width: auto;">...</a></div><div class="TabRight"></div></div><div style="position:absolute;width:0px;height:0px;overflow:visible;top:100px;left:0px;" id="id_2_dndhold" class=""></div></div></div>
    </div>
    </div>
</div>



<iframe id="autoNavFrame" name="autoNavFrame" title="Main" style="display: none;" src="javascript:parent.empty();" role="presentation" tabindex="-1"> </iframe>
<!-- OpenDocument needs this Iframe as a target for OpenDocument links to be shown in a tab in InfoView -->
<iframe name="infoviewOpenDocFrame" style="display: none" src="javascript:escape('');" role="presentation" tabindex="-1"></iframe> 


<div id="quickSearchContainer" class="yui-ac-container"><div class="yui-ac-content" style="display: none;"><div class="yui-ac-hd" style="display: none;"></div><div class="yui-ac-bd"><ul id="infoViewSearchAutoCompleteList" role="listbox" aria-owns="infoViewSearchAutoCompleteListItem0, infoViewSearchAutoCompleteListItem1, infoViewSearchAutoCompleteListItem2, infoViewSearchAutoCompleteListItem3, infoViewSearchAutoCompleteListItem4, infoViewSearchAutoCompleteListItem5" aria-label="Autocomplete search results"><li id="infoViewSearchAutoCompleteListItem0" role="option" style="display: none;"></li><li id="infoViewSearchAutoCompleteListItem1" role="option" style="display: none;"></li><li id="infoViewSearchAutoCompleteListItem2" role="option" style="display: none;"></li><li id="infoViewSearchAutoCompleteListItem3" role="option" style="display: none;"></li><li id="infoViewSearchAutoCompleteListItem4" role="option" style="display: none;"></li><li id="infoViewSearchAutoCompleteListItem5" role="option" style="display: none;"></li></ul></div><div class="yui-ac-ft" style="display: none;"></div></div><div class="yui-ac-shadow" style="width: 0px; height: 0px;"></div><iframe src="javascript:false;" frameborder="0" scrolling="no" tabindex="-1" title="Presentational iframe shim" style="position: absolute; width: 0px; height: 0px; padding: 0px;"></iframe></div>


<script type="text/javascript" src="../../shared/yui/2.8.0/connection/connection-min.js"></script>


<script type="text/javascript" src="../../shared/yui/2.8.0/container/container-min.js"></script>
<script type="text/javascript" src="../../shared/yui/2.8.0/container/assets/containerariaplugin-min.js"></script>


<script type="text/javascript" src="../../shared/yui/2.8.0/dragdrop/dragdrop-min.js"></script>
<script type="text/javascript" src="../../shared/yui/2.8.0/element/element-min.js"></script>
<script type="text/javascript" src="../../shared/yui/2.8.0/resize/resize-min.js"></script>


<script type="text/javascript" src="../../shared/yui/2.8.0/json/json-min.js"></script>


<script type="text/javascript" src="../../shared/yui/2.8.0/menu/menu-min.js"></script>


<script type="text/javascript" src="../../shared/yui/2.8.0/button/button-min.js"></script>


<script type="text/javascript" src="../../shared/yui/2.8.0/datasource/datasource-min.js"></script>
<script type="text/javascript" src="../../shared/yui/2.8.0/autocomplete/autocomplete-min.js"></script>


<script type="text/javascript" src="../../shared/yui/2.8.0/selector/selector-min.js"></script>





<script type="text/javascript" src="../../PerformanceManagement/scripting/bobjui/dash/lib/prototypeScriptaculousCompressed.js"></script>
<script type="text/javascript" src="../../PerformanceManagement/scripting/bobjui/dash/CDashboardTabOnlyMerge.js"></script>
<script type="text/javascript" src="../../PerformanceManagement/scripting/bobjui/dash/resource/ViewDashboard_msg_en.js"></script>





<script type="text/javascript" src="../../shared/js/accessibility/accessibility_util.js"></script>
<script type="text/javascript" src="../../InfoView/js/dialog.js"></script>


<script type="text/javascript" src="../../shared/js/caf/callback.js"></script>


<script type="text/javascript" src="../../InfoView/js/tabs.js"></script>


<script type="text/javascript" src="../../InfoView/js/iframeUtils.js"></script>


<script type="text/javascript" src="../../shared/yui/2.8.0/layout/layout-min.js"></script>
<script type="text/javascript" src="../../shared/layout/layout.js"></script>
<script type="text/javascript" src="../../shared/layout/layout-utils.js"></script>
<link rel="stylesheet" type="text/css" href="../../shared/layout/layout.css">


<script type="text/javascript" src="../../shared/encoder/encoder.js"></script>
<link rel="stylesheet" type="text/css" href="../../shared/dialogservice/dialogservice.css">
<script type="text/javascript" src="../../shared/dialogservice/dialogservice_strings_en.js"></script>
<script type="text/javascript" src="../../shared/dialogservice/dialogservice.js"></script>


<script type="text/javascript">
INFOVIEW.invokeCafAction = getCafActionViewerCallback();
INFOVIEW.invokeGlobalAction = getCafActionCallback();
</script>


<script type="text/javascript" src="../js/listing_main_b.js"></script>


<script type="text/javascript">
var btToken = 'MDAwRGZgNT1TRj9VV2FHMWNpYmpBWjNWQ1dPUE43ODAEQ';
		 

    var isMainWindow = true;
    var appKind = "InfoView";
    var logoffUrl  = "../logon/logoff.do?bttoken=MDAwRGZgNT1TRj9VV2FHMWNpYmpBWjNWQ1dPUE43ODAEQ";
    var timeoutUrl = "../logon/logoff.do?timeout=true&bttoken=MDAwRGZgNT1TRj9VV2FHMWNpYmpBWjNWQ1dPUE43ODAEQ";
    var parentMethod = '';
    var commonDomain = '';

</script>

<script type="text/javascript" src="../../shared/pinger/pinger_strings_en.js"></script>
<script type="text/javascript" src="../../shared/pinger/pinger.js"></script>


<script type="text/javascript" src="../../shared/js/app/portal_utils.js"></script>






    <script type="text/javascript">
    // Communicate to parent frames to faciltate session management
    var embedded = 'null' === 'true';     
    
    var renderRtl=false
                
    if (embedded && parentMethod != '') {         
        var embeddedLogoffUrlPath = '/InfoView/logon/logoff.do?sapEPEmbedded=true&appKind=InfoView&bttoken=MDAwRGZgNT1TRj9VV2FHMWNpYmpBWjNWQ1dPUE43ODAEQ';
        var embeddedLogoffUrl = location.href.substr(0, location.href.indexOf('/InfoView')) + embeddedLogoffUrlPath;
       
        var strictDomain = 'null' === 'true';
        
        var parameters = {
                strictDomain : strictDomain,
                parentMethod: parentMethod,
                serializedSession: '3&5U=6453617J0MEmkVSz9Ne6GapOaz3GBurx25wPggCe6453616JSR5S5M4LEncsrZ5GAobIbBRPtkZBjiCO,8P&10U,88&1,8P&63=token,8P&35=w547dc6,8P&S5,88&pa,8P&ua=AWmaEx4Z.NVPpAEthuTGAjc,8P&ub=AX5sx7Fq4TJFnl8Q4.nthD8,8P&zA,83&4E=6453616JSR5S5M4LEncsrZ5GAobIbBRPtkZBjiCO,8P&3k=@ibsbusint.opac,8P&4F=4419737,8P&Tm=36500,83&Tn={3&U=3,83&.1={3&2=4419738,83&O=FavoritesFolder,8P},?z&.2={3&2=4419739,83&O=PersonalCategory,8P},?z&.3={3&2=4419740,83&O=Inbox,8P},?z},?z&7r,83&2r=swdwbo02.fisglobal.com:6400,8P&lu=1033,83&PP=1024,83&ux=AeOfiOOdrOpFuWi1pXC.yDA,8P&uy=-62,8L',
                cmsName: 'swdwbo02.fisglobal.com:6400',
                logoffUrl: embeddedLogoffUrl,
                refresh: true,
                setParentDomain: true,
                commonDomain: commonDomain,
                iViewAutoLogOff: 'true' === 'true',
				appKind: 'InfoView',
				bttoken:'bttoken=MDAwRGZgNT1TRj9VV2FHMWNpYmpBWjNWQ1dPUE43ODAEQ'
        }    
        businessobjects.portal.communicateSessionInfoToAncestorFrame(parameters);    
    }
     
    </script>


<div id="divHome-4419737" class="yui-layout" style="position: absolute; visibility: visible; left: 0px; width: 401px; height: 585px; top: 69px; display: block;"><div class="yui-layout-doc" style="height: 585px; width: 401px;"><div id="yui-gen0" class="yui-layout-unit yui-layout-unit-center yui-layout-noscroll" style="position: absolute; height: 585px; width: 401px; top: 0px; left: 0px;"><div class="yui-layout-wrap" id="yui-gen1" style="height: 585px; width: 401px; top: 0px; left: 0px;"><div class="yui-layout-bd yui-layout-bd-nohd yui-layout-bd-noft" style="height: 583px; width: 399px; top: 0px;"><div id="innerDivHome-4419737" style="height: 585px; width: 401px;"><iframe frameborder="0" id="iframeHome-4419737" tabindex="-1" src="https://ibsbusint-system.fnfis.com/BOE4/BOE/portal/1603120824/InfoView/listing/home.do?appKind=InfoView&amp;bttoken=MDAwRGZgNT1TRj9VV2FHMWNpYmpBWjNWQ1dPUE43ODAEQ" style="width: 401px; height: 585px;"></iframe></div></div></div></div></div></div><div class="spinnerMask" style="width: 401px; height: 657px; display: none;"></div><div class="spinner" style="left: 100px; top: 308px; display: none;"><div>Loading...</div></div><div id="BusinessObjects.client.common.GarbageBin.garbageBin" style="display: none; visibility: hidden;"></div></body></html>
