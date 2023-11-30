# elk-aggrgations
ELK Aggegations Demo
Analyzing Car Data with Elasticsearch: A Bulk Insert and Aggregation Scenario
Today, let's delve into a scenario where we use Elasticsearch to store and analyze data related to car sales. In this particular case, we perform bulk insert operations and conduct various aggregations to gain insights into the dataset. The provided Elasticsearch queries and commands showcase a range of functionalities, from mapping and searching to aggregation.

Bulk Inserting Car Data
To start with, we use a bulk insert operation to add car sales data to the Elasticsearch index. Each document represents a car sale and includes details such as price, color, make, and the date it was sold. The bulk insert operation is an efficient way to add multiple documents simultaneously, enhancing the overall performance.

Aggregating Data: Making Sense of the Numbers
Aggregating by Car Make
Let's start with a simple aggregation by the car make. This provides a breakdown of the number of sales for each make.

Aggregating by Color with Extended Stats on Price
To delve deeper, we aggregate the data based on the color of the cars. Additionally, we calculate extended statistics on the price within each color category.
