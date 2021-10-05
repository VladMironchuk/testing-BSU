[Softtour](https://www.softtour.by/).

#Functional Test Cases

## Test case 1
  Steps:  
    1. Go to https://www.softtour.by/round-selection  
    2. Click "Подобрать" button. 
    3. Select "Дата" in "Сортировать по" field.<br> 
    4. In "А-я" toggle arrow down.<br> 
  Expected Result:  
    List of hotels sorted by date from early to late. 
    
## Test case 2
  Steps:  
    1. Go to https://www.softtour.by/round-selection. 
    2. Click "Подобрать" button. 
    3. In search section "РЕЗУЛЬТАТЫ ПОИСКА С ВОЗМОЖНОСТЬЮ ФИЛЬТРАЦИИ, СОРТИРОВКИ" select "4" in "Рейтинг от". 
    4. In search section "РЕЗУЛЬТАТЫ ПОИСКА С ВОЗМОЖНОСТЬЮ ФИЛЬТРАЦИИ, СОРТИРОВКИ" set "2000" in "Цена от" and "2400" in "Цена до". 
    5. In search section "РЕЗУЛЬТАТЫ ПОИСКА С ВОЗМОЖНОСТЬЮ ФИЛЬТРАЦИИ, СОРТИРОВКИ" click "Применить". 
  Expected Result:  
    List of hotels whose price is from 2000 to 2400. 
    
 ## Test case 3. 
   Steps:  
    1. Go to https://www.softtour.by/tours/promotion. 
    2. Click "Показать" button. 
   Expected Result:  
    In search list display message "Нет найденных туров". 
 
 ## Test case 4. 
   Steps:  
    1. Go to https://www.softtour.by/hotels/turkey/viva-ulaslar-hotel-4. 
    2. Click "Отель в Google" button. 
   Expected Result:  
    Yandex map is replaced with Google maps. 

 ## Test case 5. 
   Steps:  
    1. Go to https://www.softtour.by/. 
    2. Click "Подобрать" button. 
   Expected Result:  
    Should be redirect to https://www.softtour.by/round-selection/uae. 
    
 ## Test case 6. 
   Steps:  
    1. Go to https://www.softtour.by/round-selection. 
    2. In "Страна" section select "Транзания". 
   Expected Result:  
    Should be redirect to https://www.softtour.by/round-selection/tanzania. 

## Test case 7
   Steps:
    1. Go to https://www.softtour.by/round-selection
    2. In "Страна" section select "Транзания"
   Expected Result:
    Title of page is replaced with "Подбор тура в Танзанию из Минска, Москвы и Киева в режиме онлайн"
    
## Test case 8
   Steps:
    1. Go to https://www.softtour.by/round-selection
    2. In subtitle section click red text "Как пользоваться подбором тура?"
   Expected Result:
    The instruction must be display as drop-down section
    
## Test case 9
   Steps:
    1. Go to https://www.softtour.by/
    2. Navigate to fourth slide in slider
    3. Click "Подробнее" link
   Expected Result:
    You will be redirect to https://www.softtour.by/tour/country/egypt/hot/town/minsk/usd/net/albatros/category/4*,5*/food/ai,uai
    
## Test case 10
   Steps:
    1. Go to https://www.softtour.by/hotels/turkey/larissa-blue-3
    2. Click "Оставить заявку"
    3. In pop-up window click "Отправить"
   Expected Result:
    Validation of required field "Контактный телефон" is show
