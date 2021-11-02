# Todo List
Тестовое задание на позицию FullStack        
# Описание проекта
Требования: сделать список задач с ролевым доступом по установленным правилам и возможностью оповещения при изменениях     
# Реализовано
+ Таблицы статусов в БД заполняются из enum - визуально достаточно наглядно      
+ Настраиваемый Filter для бд инкапсулирован в отдельный класс        
+ Спискок задач в формате таблицы (Read-Create-Update)             
+ Ввод даты - в формате календаря       
+ Логгирование, IRepository, IRules    
+ Реализованы базовые требованя, кроме аутентификации       
# Установка
Клонируйте проект, впишите свой connection string в appsettings.Development.json    
Запустите проект в Visual Studio, подождите пока установятся node_modules      
Для добавления заполненной задачи в бд выберите в меню SeedDB - при нажатии кнопки Seed будет добавлена одна шаблонная задача  
# .NET Core 5.0 = React = Bootstrap = MSSql   
NuGet: EFCore, Swagger    
README будет изменён по мере доработки проекта    
