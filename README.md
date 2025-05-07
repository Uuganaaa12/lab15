# lab15# Тооцоолуур Төсөл

Энэ бол энгийн Java тооцоолуурын төсөл. Энэ төсөл нь Maven суурьтай бөгөөд Git workflow ба GitHub Actions-ийг хэрэглэн баг хамт олноор хөгжүүлж болохыг харуулна.

## Төслийн бүтэц
- `src/main/java/lab15/sict/must/edu/mn`: Анхдагч Java кодын директор
- `src/test/java/lab15/sict/must/edu/mn`: JUnit тестийн директор
- `checkstyle.xml`: Кодын загварын шалгалтын дүрмүүд
- `pom.xml`: Maven Project Object Model файл

## Хэрхэн угсрах/ажиллуулах
- `mvn test`: JUnit тестүүдийг ажиллуулах
- `mvn checkstyle:check`: Кодын загварыг шалгах
- `mvn jacoco:report`: Кодын хамрагдалтын тайлан үүсгэх
- `mvn clean install`: Төслийг цэвэрлэж, угсрах

## Шаардлагууд
- Java 17
- Maven 3.6+git add .