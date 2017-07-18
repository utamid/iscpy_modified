# iscpy_modified
iscpy modified python library. Additional features such as adding zone and write to file

## Usage

```
ParseISCString(isc_string)
```
Returns `parsed bind config file` in python dictionary format(ISC dictionary) and `keys` without childkeys e.g. include

```
AddZone(json_zone, isc_string)
```
Adding zone(s). Input is in json string. Returns ISC dictionary with added zone(s). This method doesn't include writing to output file

```
WriteToFile(isc_dict, isc_specialkeys, filename)
```
Write ISC dictionary to a file
