package frontierX.pages;

import org.openqa.selenium.WebDriver;
import org.openqa.selenium.WebElement;
import org.openqa.selenium.support.FindBy;

public class LoginPage extends BasePage {

	//	Creating WebElements
	@FindBy(id = "email")
	private WebElement username ;
	
	@FindBy(id = "password")
	private WebElement password ;
	
	@FindBy(xpath = "//input[@value='Login']")
	private WebElement loginButton ;
	
//	@FindBy(id = "keepLoggedInCheckBox")
//	private WebElement rememberCheckbox ;
//	
//	@FindBy(linkText = "Forgot your password?")
//	private WebElement forgotPasswordLink ;
	
	
	//	Constructor
	public LoginPage(WebDriver driver) {
		super(driver);
	}
	
	//	Creating Action Methods
	public HomePage login(String usernameValue, String passwordValue) {
		username.sendKeys(usernameValue);
		password.sendKeys(passwordValue);
		loginButton.click();
		return new HomePage(driver);
	}
	
//	public void clickRememberCheckBox() {
//		rememberCheckbox.click();
//	}
//	
//	public void forgotPasswordLink() {
//		forgotPasswordLink.click();
//	}
	
	
}
