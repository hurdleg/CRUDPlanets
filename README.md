## CRUD ##
  CRUD app for the Planets:
  * **C**reate - create a new planet (Pluto) on the web service
  * **R**ead|**R**etrieve - get collection (array) of planets from the web service
  * **U**pdate - update planet Pluto on the web service
  * **D**elete - delete planet Pluto on the web service

## Usage ##

1. First launch: list of planets by distance from Sun
    * Toast planet count: 8 (9 if Pluto exists on the web service)
2. **Menu > 2. Create a new Planet (Pluto)**
    * Toast: POST Pluto
    * Toast planet count: 9
    * Observe: Pluto has been created on the web service, and the image is _No Image Found_
3. **Menu > 3. Update Pluto to hurdleg**
    * Toast: PUT hurdleg
    * Toast planet count: 9
    * Observe: Pluto has been updated on the web service, and the image & name have been changed
4. **Menu > 4. Delete Pluto**
    * Toast: DELETE hurdleg
    * Toast planet count: 8
    * Observe: Pluto has been removed from the web service
5. **Menu > 5. Delete Bogus Planet**
    * Toast: 404
    * Observe: 404 means the planet is not found on the web service

## Code Inspection ##

  See my //TODO comments: **View > Tool Windows > TODO**

## Source Code ##

  Available from GitHub:

  <https://github.com/hurdleg/CRUD.git>

## Reference ##

  Based on _Send parameters in a POST request_  in _Android App Development: RESTful Web Services_ with David Gassner