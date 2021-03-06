
Controller :: getParentRecords
-------------------------------------------

Return the IDs of all child records of a particular record.


### Description ###

**Definition:** `protected function getParentRecords($strTable, $intId)`

**Located in:** *system/libraries/Controller.php*

**Class hierarchy:** *[System](../System.md) > [Controller](../Controller.md)*


### Parameters ###

1. *string* `$strTable`

	A name of the table to be executed.

2. *integer* `$intId`

	The numberic ID of parent record.


### Return Values ###

An array containing IDs of child records of the specified parent record.


### See also ###

- [`Controller::getChildRecords`](getChildRecords.md) – Get the child records


