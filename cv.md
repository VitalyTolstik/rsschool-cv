# Vitali Toustsik

![image](https://user-images.githubusercontent.com/62697094/206762789-3eb3a08f-d941-47ae-a31f-5e9922aaa589.png)

## Contacts

* Location: Minsk, Belarus
* Phone: +375 29 3400778
* Email: vital.tol90@gmail.com
* GitHub: [vitalytolstik](https://github.com/VitalyTolstik)

## About me

I like to read books, learn new technologies, I like to work in a team and alone, I have experience working with foreign customers, work in the upsell department, currently I work in an outsourcing company as QA Automation engineer

## Skills

* Java
* Serenity-BDD
* Cucumber
* TestNG
* RestAssured
* Git
* Appium
* Maven

## Code Example

```
    @Step
    public boolean isOddsFormatCorrect(String oddsFormat) {
        openNoMarketLayoutIfPresent();
        return oddsLabels().stream()
                .findFirst()
                .orElseThrow(() -> new NoSuchElementException("Can't find spread bet element"))
                .waitUntilVisible()
                .getText()
                .substring(ZERO, ONE)
                .matches(getOddsFormat(oddsFormat).getRegularExpression());
    }
 ```
 
## Experience
 
 01.03.2020 - present "Outsource company". 
 
## Education

* University: Belarusian National Technical University, Powder metallurgy engineer
* Courses:
IT Academy (Java SE, Java EE)
Streamline (A2, B1)

## English

B1
