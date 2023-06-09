![Визуализация0](https://user-images.githubusercontent.com/96602226/231869811-1e2ff157-b957-459d-8627-6d684334fd04.png)


## Probation project
Проект подготовки и визуализации данных

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;I. этап. Данный проект является реализацией [тестового задания](https://docs.google.com/document/d/1QCxiYl1hNCaz8FnTdZcQYlpEvCqTAktY7HIkd9egFsc/edit?usp=sharing)
по подготовке и визуализации данных исходно размещенных в Google Sheet с использованием Jupiter Notebook, фреймворков pandas, numpy, matplotlib c реализацией subplots модулем gridspec, фильтрацией записей с пропусками, неформатными текстовыми и недесятичными цифровыми значениями записей датафрейма с использованием модулем re (regular expressions) на основе шаблонов.  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;В процессе реализации проекта произведена выгрузка данных из Google Sheet [по ссылке](https://docs.google.com/spreadsheets/d/165sp-lWd1L4qWxggw25DJo_njOCvzdUjAd414NSE8co/edit?usp=sharing) в pandas dataframe, проведена обработка и фильтрация пропусков и модулем re по шаблонам, записи, содержащие неформатные значения удалены, количество удалённых записей составило 0,48 %, что считаем в пределах допустимых значений, не оказывающее влияния на результаты последующего исследования.  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Далее нами проведены необходимые настройки Google API в платформе Google Cloud, загружены необходимые модули, обеспечивающие аутентификацию и доступ к Google Sheets и 
Google Drive, обработанные данные [выгружены в облако](https://docs.google.com/spreadsheets/d/165sp-lWd1L4qWxggw25DJo_njOCvzdUjAd414NSE8co/edit?usp=sharing) для обеспечения доступа пользователей.  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;II. этап. Выполнена визуализация диаграмм рассеяния сгруппированных по 'area' и 'cluster' данных, в соответствии с требованиями задания 
с использованием модуля gridspec, выполнено сохранение графиков c параметрами в соответствии с условиями задания. </p>

![Визуализация_комбо](https://user-images.githubusercontent.com/96602226/231873225-ee7c7048-888a-41c2-aaa7-b4b4ae71bfd2.jpg)
