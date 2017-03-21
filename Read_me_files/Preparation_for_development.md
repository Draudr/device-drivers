
[Главная страница](https://github.com/Draudr/device-drivers/blob/master/README.md) > Подготовка к разработке
> * Ниже описаны шаги, которые необходимо выполнить прежде, чем приступтаь к разработке драйверов, описанной в других разделах.  
> * Здесь и далее по тексту все имена констант указаны из `ru.evotor.devices.drivers.Constants`.  

<a name="1101"></a>
# __1.1. Подготовка к разработке.__

_Содержание:_   
1.1.1. [Подключение библиотеки для работы с оборудованием к своему проекту.](#101)  

<a name="101"></a>
## 1.1.1. Подключение библиотеки для работы с оборудованием к своему проекту.
Для этого в `build.gradle` проекта добавьте ссылку на репозиторий jitpack:

```
allprojects {
    repositories {
        jcenter()
        maven { url 'https://jitpack.io' }
    }
}
```

в модуле `build.gradle` добавьте зависимость и укажите точную версию (текущая: 1.2.0+):

```
dependencies {
    compile 'com.github.evotor:device-drivers:1.2.0+'
}
```
<a name="102"></a>

-----
###### Более подробную информацию по разрабатке своих решений для бизнеса на платформе Эвотор, Вы можете найти на нашем сайте для разработчиков: https://developer.evotor.ru/