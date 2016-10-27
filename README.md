# wor-scopes
Metadata for wor-scopes collection

metadata was pulled from UTKcataloging and the identifier
for the admindb was used to rename the files.

The Omeka id was also dropped.

## Additional Updates ##
* Added an oXygen Project (`wor-scopes.xpr`).
* Added an identity transform that updates the `/mods/relatedItem[@type='host'][@displayLabel='Project']/titleInfo/title` to "Of Monkeys and Men: Public and Private Views from the Scopes Trial".
* Added an `output/` directory for files coming out of the identity transform.
* There are transform and validation scenarios included in the project. 
    * Open the wor-scopes.xpr using oXygen.
    * In the Project View, do the following:
    * (_note:_ this step has already been done) Right-click on the `wor-scope-mods` directory and select **Transform** > **Apply Transformation Scenario(s)**
    * ...wait a moment...
    * (_note:_ this step has already been done) After the transform is complete, right-click on the `output` directory and select **Validate** > **Validate** to check all the files in the directory.