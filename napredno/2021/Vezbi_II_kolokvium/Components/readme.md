# Компоненти (40 поени) Problem 4 
Да се дефинира класа Component во која се чуваат:

- бојата
- тежината
- колекција од внатрешни компоненти (референци од класата Component).
 
Во оваа класа да се дефинираат методите:

- Component(String color, int weight) - конструктор со аргументи боја и тежина
- void addComponent(Component component) - за додавање нова компонента во внатрешната колекција (во оваа колекција компонентите секогаш се подредени според тежината во растечки редослед, ако имаат иста тежина подредени се алфабетски според бојата).

Да се дефинира класа Window во која се чуваат:

- име
- компоненти.

Во оваа класа да се дефинираат следните методи:

- Window(String) - конструктор
- void addComponent(int position, Component component) - додава нова компонента на дадена позиција (цел број). На секоја позиција може да има само една компонента, ако се обидеме да додадеме компонента на зафатена позиција треба да се фрли исклучок од класата InvalidPositionException со порака Invalid position [pos], alredy taken!. Компонентите се подредени во растечки редослед според позицијата.
- String toString() - враќа стринг репрезентација на објектот (дадена во пример излезот)
- void changeColor(int weight, String color) - ја менува бојата на сите компоненти со тежина помала од проследената
- void swichComponents(int pos1, int pos2) - ги заменува компонените од проследените позиции.