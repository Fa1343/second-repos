# # temperature_converter.py

print("🌡️ مبدل دما 🌡️")
print("انتخاب کن:")
print("1 - تبدیل سلسیوس به فارنهایت")
print("2 - تبدیل فارنهایت به سلسیوس")

choice = input("انتخاب شما (1 یا 2): ")

if choice == "1":
    celsius = float(input("دما به سلسیوس: "))
    fahrenheit = (celsius * 9/5) + 32
    print(f"{celsius}°C = {fahrenheit}°F")
elif choice == "2":
    fahrenheit = float(input("دما به فارنهایت: "))
    celsius = (fahrenheit - 32) * 5/9
    print(f"{fahrenheit}°F = {celsius}°C")
else:
    print("❌ انتخاب نامعتبر!")
second-repo
