# Kollok_cringe_2024

Выполнение коллоквиума по КиТГ в ЛЭТИ

## Внешние зависимости

Добавьте в ваш проект следующие зависимости:

1. math-system
   - Скачайте файл `math-system-1_0-SNAPSHOT.jar` и добавьте его в ваш проект в папку `lib`.
   - При необходимости обновите путь к файлу в файле `pom.xml`.
  
   ```xml
    <project ...>
        ...
        <dependencies>
            <dependency>
                <groupId>com.example</groupId>
                <artifactId>math-system</artifactId>
                <version>1.0-SNAPSHOT</version>
                <scope>system</scope>
                <type>jar</type>
                <!-- Измените следующий путь, при обновлении пакета math-system -->
                <systemPath>${project.basedir}/libs/math-system-1_0-SNAPSHOT.jar</systemPath> 
            </dependency>
            ...
        </dependencies>
    </project>
   ```
