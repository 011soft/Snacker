# SNACKER

Snacker is an open-source database with the goal of being an ever-growing and adapting database that can be referenced by any app to track anything from dietary restrictions to cooking times. The idea is that any software can implement Snacker to search a food using a search or scanning a barcode, and access any relevant information that could be asked for.

## Use cases

- A mobile app that lets you track your calories and nutrients
- A smart oven that scans your food to automatically pre-heat and set cook time
- A smartphone app that lets you quickly check in the store what foods are friendly to your allergies
- A website that tells you what foods fit your dietary restrictions

## Datapoints

Currently, the database is designed to track the following information:

- All nutrients that are recorded on an FDA Nutrition Facts label
- The product name, and all applicable UPC tags
- Caffiene and Alcohol measurements
- Ingredients, as reported by FDA Nutrition Facts label
  - Major and Minor Allergens
  - Dietary restrictions
- Common pairings
- Labels, both required and not, like Non-GMO labels

For more information on any of these datapoints, please see [the wiki](https://github.com/shawnshyguy/Snacker/wiki).

## Community and contribution

One major goal of this project is to keep it as updated and relevant as possible. To achieve this, Snacker will be open to contribution. If a piece of information is missing, incorrect, duplicated, or incomplete, users are welcome to contribute correct data to the database.