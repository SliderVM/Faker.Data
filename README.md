# Faker
Faker is a C# library used to easily generate fake data for: names, address, and many more!

К сожалению NuGet пока не поддерживается. Возможно в будущем будет.

## Usage

#### Addresses
```
var state = Faker.Address.State();
var stateAbbr = Faker.Address.StateAbbreviation();
var provinceAbbr = Faker.Address.ProvinceAbbreviation();
var province = Faker.Address.Province();
var streetName = Faker.Address.StreetName();
var country = Faker.Address.Country();
var cityPrefix = Faker.Address.CityPrefix();
var citySuffix = Faker.Address.CitySuffix();
var secondaryAddress = Faker.Address.SecondaryAddress();
var usCity = Faker.Address.USCity();
var usCounty = Faker.Address.USCounty();
var canadianZip = Faker.Address.CanadianZip();
var usZip = Faker.Address.USZip();
var rusCity = Faker.Address.RusCity(); - получить российский город
```
#### Name
```
var maleName = Faker.Name.MaleFirstName();
var femaleName = Faker.Name.FemaleFirstName();
var first = Faker.Name.FirstName();
var full = Faker.Name.FullName();
var last = Faker.Name.LastName();
var gender = Faker.Name.Gender();
var ethnicity = Faker.Name.Ethnicity();
var Patronymic = Faker.Name.Patronymic(); - Возвращает случайное отчество
```
#### Geo Location
```
var lat = Faker.GeoLocation.Latitude();
var lon = Faker.GeoLocation.Longitude();
```
#### Colors
```
var rgb = Faker.Color.RGB();
var hex = Faker.Color.Hex();
var systemColor = Faker.Color.SystemColor();
var color = Faker.Color.ColorString();
```
#### Numbers
```
var randomNumber = Faker.Number.RandomNumber();
var randomNumber1 = Faker.Number.RandomNumber(10);
var randomNumber2 = Faker.Number.RandomNumber(10,20);
var negativeNumber = Faker.Number.NegativeNumber(10);
var evenNumber = Faker.Number.Even(0,50);
var oddNumber = Faker.Number.Odd(0,50);
var doubleNumber = Faker.Number.Double();
var boolResult = Faker.Number.Bool();
```
#### Image
```
var jpeg = Faker.Images.JPEG();
var bmp = Faker.Images.BMP();
var png = Faker.Images.PNG();
```
#### Internet
```
var host = Faker.Internet.Hosts();
var ipv4 = Faker.Internet.IPv4();
var ipv6 = Faker.Internet.IPv6();
var macAddress = Faker.Internet.Mac();
var localhost = Faker.Internet.LocalHost();
var protocol = Faker.Internet.Protocol();
var topDomainSuffix = Faker.Internet.TopDomainSuffix();
var topCountrySuffix = Faker.Internet.TopCountryDomainSuffix();
var domainSuffix = Faker.Interent.DomainSuffix();
```
#### Credit Card
```
var type = Faker.CreditCard.CreditCardType();
```
#### Date
```
var between = Faker.Date.Between();
var birthday = Faker.Date.Birthday();
var forwardTime = Faker.Date.ForwardWithTime();
var forwardTime1 = Faker.Date.ForwardWithTime(1, 1, 1);
var forward = Faker.Date.Forward(1, 1, 50);
var forward1 = Faker.Date.Forward();
var past = Faker.Date.Past(1, 1, 1);
var past1 = Faker.Date.Past();
var pasteTime = Faker.Date.PastWithTime();
var pasteTime1 = Faker.Date.PastWithTime(1, 1, 1);
var recent = Faker.Date.Recent(5);
var monthShort = Faker.Date.MonthShort();
var month = Faker.Date.Month();
var weekday = Faker.Date.Weekday();
var day = Faker.Date.Day();
var year = Faker.Date.Year();
```
#### Lorem
```
var word = Faker.Lorem.Word();
var words = Faker.Lorem.Words();
var letter = Faker.Lorem.Letter();
var letters = Faker.Lorem.Letters(4);
var letters1 = Faker.Lorem.Letters();
var sentence = Faker.Lorem.Sentence(7);
var sentence1 = Faker.Lorem.Sentence();
var sentences = Faker.Lorem.Sentences(3);
var sentences1 = Faker.Lorem.Sentences();
var paragraph = Faker.Lorem.Paragraph(2);
var paragraph1 = Faker.Lorem.Paragraph();
var paragrahps = Faker.Lorem.Paragraphs();
var paragraphs1 = Faker.Lorem.Paragraphs(2);
```
#### User
```
var  = Faker.User.Username();
var  = Faker.User.Email();
var  = Faker.User.Password();
var  = Faker.User.Password(3);
var  = Faker.User.Password(10, false);
var  = Faker.User.Password(10, true);
var  = Faker.User.Password(10, 2);
```

