# myNewRepo

public void takeScreenshot(String tcNum) throws IOException {
		BAsic dri = new BAsic();
		driver = dri.driverInit();
		//Source file
		File source = ((TakesScreenshot)driver).getScreenshotAs(OutputType.FILE);
		Date date = new Date();	
		
		
