 ChromeDriver driver = new ChromeDriver();
		 driver.get("https://www.zomato.com/lucknow"); 
		 driver.manage().window().maximize();
		 driver.manage().timeouts().implicitlyWait(Duration.ofSeconds(20));
         driver.findElement(By.xpath("//li[@class = 'sc-3o0n99-4 kAUthO'][2]")).click();
		 driver.switchTo().frame("auth-login-ui");
		 driver.findElement(By.cssSelector("input[placeholder='Phone']")).sendKeys("9984223065");
		 driver.findElement(By.cssSelector("input[placeholder='Phone']")).clear();
		
