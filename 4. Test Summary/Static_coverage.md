# Результаты использования статики на странице стажировки

С помощью DevTools было проверено, сколько процентов статики  не используется на странице:
Результат:
![static_coverage](../5.%20Images/static-coverage.png)

## Самые неиспользуемые CSS файлы:
| CSS-файл                    | Не используется |
| --------------------------- | --------------: |
| `jivosite.css` (`.default`) |       **51,1%** |
| `internship.css`            |       **48,7%** |
| `custom.css`                |       **37,7%** |
| `widget.css`                |        **7,8%** |
| `styles.css`                |        **5,8%** |
| `jivosite.css` (`bpmsoft`)  |        **0,2%** |

## Самые неиспользуемые JS файлы:

| JS-файл                   | Не используется |
| ------------------------- | --------------: |
| `init-tabs.js`            |        **100%** |
| `init-drop-form.js`       |        **100%** |
| `bundle.js`               |        **100%** |
| `locale-ru-RU-json.js`    |        **100%** |
| `carousel.js`             |       **89,2%** |
| `/internship/`            |       **88,4%** |
| Jivo `widget`             |       **78,3%** |
| `tabs-scrolling.js`       |       **65,5%** |
| `overflow-detector.js`    |       **62,4%** |
| `Tabs.js`                 |       **62,2%** |
| `model.js`                |       **60,1%** |
| `template_..._v1.js`      |         **56%** |
| `protobuf.js`             |       **42,9%** |
| `page_..._v1.js`          |       **38,4%** |
| `core.js`                 |       **35,4%** |
| `DropForm.js`             |       **30,5%** |
| `core_promise.js`         |       **29,6%** |
| `burger-menu.js`          |         **27%** |
| `pull.client.js`          |       **18,5%** |
| `rest.client.js`          |       **11,8%** |
| `ScrollTabsWithButton.js` |        **2,5%** |
| `OverflowDetector.js`     |        **2,5%** |
| `ScrollTabs.js`           |        **3,4%** |
