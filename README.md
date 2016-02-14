# mzd-connect-additional-apps
MZD Connect: Enhanced integration for custom apps

For local development, add the following lines to /jci/gui/framework/test/DebugTest.js:

    case "SelectDriveRecord":
     framework.debug.fakeCtxtChgMsgs("vdt", "DriveChartDetails");
     break;
