# Protection_of_clients_personal_data_LAG

**Description:**

We have access to the personal data of an insurance company's clients. It's necessary to protect the clients' data by developing a method of data transformation that makes it difficult to recover personal information. Justify the correctness of its operation. Also, protect the data in such a way that the quality of machine learning models does not deteriorate during the transformation. There's no need to choose the best model.

**Objective:** Find and justify a method of encrypting personal data without losing the quality of the machine learning model.

**Tasks:**

- Load and study the data.
- Answer and justify the solution to the question: "Features are multiplied by an invertible matrix. Will the quality of linear regression change? (It can be retrained.)"<br>
        a. It will change. Provide examples of matrices.<br>
        b. It will not change. Indicate how the parameters of linear regression are related in the original problem and the transformed one.
- Propose an algorithm for data transformation to solve the problem. Justify why the quality of linear regression will not change.
- Program this algorithm using matrix operations. Verify that the quality of the linear regression from sklearn does not differ before and after transformation. Apply the R2 metric.

**Data Description:**

- Features: insured's gender, age, salary, and the number of family members.
- Target feature: the number of insurance payouts to the client in the last 5 years.

**Описание:**

В нашем распоряжение есть личные данных клиентов страховой компании. Необходимо защитить данные клиентов, разработать такой метод преобразования данных, чтобы по ним было сложно восстановить персональную информацию. Обосновать корректность его работы. Также нужно защитить данные так, чтобы при преобразовании качество моделей машинного обучения не ухудшилось. Подбирать наилучшую модель не требуется.

**Цель:** Найти и обосновать способ шифрования персональных данных без потери качества модели машинного обучения.

**Задачи:**

- Загрузитб и изучите данные.
- Ответить на вопрос и обосновать решение: "Признаки умножают на обратимую матрицу. Изменится ли качество линейной регрессии? (Её можно обучить заново.)"<br>
        a. Изменится. Приведите примеры матриц.<br>
        b. Не изменится. Укажите, как связаны параметры линейной регрессии в исходной задаче и в преобразованной.
- Предложить алгоритм преобразования данных для решения задачи. Обосновать, почему качество линейной регрессии не поменяется.
- Запрограммировать этот алгоритм, применив матричные операции. Проверить, что качество линейной регрессии из sklearn не отличается до и после преобразования. Применить метрику R2.

**Описание данных:**

- Признаки: пол, возраст и зарплата застрахованного, количество членов его семьи.
- Целевой признак: количество страховых выплат клиенту за последние 5 лет.
