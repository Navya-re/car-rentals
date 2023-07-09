# Starter Repo
This repo has everything you need to get started on the program, good luck!
class diagram
Car rentals class diagram
+------------------------------------+
|           CarServicing             |
+------------------------------------+
| - criteriaMap: Map<CarType, ServiceCriteria> |
+------------------------------------+
| + addServiceCriteria(carType: CarType, criteria: ServiceCriteria): void |
| + removeServiceCriteria(carType: CarType): void |
| + getServiceCriteria(carType: CarType): ServiceCriteria |
| + isServiceRequired(car: Car): boolean |
+------------------------------------+
               /_\
                |
                |
                |
                |
                V
+------------------------------------+
|             CarType                 |
+------------------------------------+
| - name: string                      |
| - engine: Engine                    |
| - battery: Battery                  |
| - tire: Tire                        |
+------------------------------------+
| + getName(): string                 |
| + getEngine(): Engine               |
| + getBattery(): Battery             |
| + getTire(): Tire                   |
+------------------------------------+
                    |
                    |
                    |
                    |
                    V
+------------------------------------+
|             Engine                  |
+------------------------------------+
| - type: string                      |
+------------------------------------+
| + getType(): string                 |
+------------------------------------+
                    |
                    |
                    |
                    |
                    V
+------------------------------------+
|             Battery                  |
+------------------------------------+
| - type: string                       |
+------------------------------------+
| + getType(): string                 |
+------------------------------------+
                    |
                    |
                    |
                    |
                    V
+------------------------------------+
|              Tire                   |
+------------------------------------+
| - type: string                       |
+------------------------------------+
| + getType(): string                 |
+------------------------------------+



























