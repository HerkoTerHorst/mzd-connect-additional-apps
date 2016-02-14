# MZD Connect: Enhanced integration for custom apps

For local development, follow the instructions [here](http://www.mazda3hacks.com/doku.php?id=misc:virtual2) and add the following lines to /jci/gui/framework/test/DebugTest.js in DebugTest.MmuiCallback:

    case "SelectDriveRecord":
     framework.debug.fakeCtxtChgMsgs("vdt", "DriveChartDetails");
     break;
