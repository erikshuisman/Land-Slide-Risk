AnotherConversion = "y"
while AnotherConversion == "y":
    print("Temperature Converter")
    degreeChoice = input("Enter 1 for Fahrenheit to Celsius, or 2 for Celsius to Fahrenheit: ")
    firstTemp = int(input("Enter input temperature: "))
    convertedTemperature = ""
    if degreeChoice == "1":
        convertedTemperature = (firstTemp - 32) * 5 / 9
    if degreeChoice == "2":
        convertedTemperature = (firstTemp * 9/5) + 32
    if degreeChoice != "1" and degreeChoice != "2":
        print("Invalid conversion selection")
        convertedTemperature = 0
    print("The converted temperature is", convertedTemperature)
    AnotherConversion = input("Another conversion (y/n)?")
    while AnotherConversion != "y" and AnotherConversion != "n":
        AnotherConversion = input("Another conversion (y/n)?")
