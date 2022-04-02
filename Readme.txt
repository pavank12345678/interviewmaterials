only interview materials

@Test
	public void rc006() throws InterruptedException
	{
		String parent= driver.getWindowHandle();
		System.out.println("The window name"+driver.getTitle());
	WebElement button=driver.findElement(By.id("openwindow"));
	button.click();
	