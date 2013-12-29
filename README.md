Python script which will generate java classes based on a set of arguments.

Desired usage: python jgen class-name -var [mod][type][name] -mtd [mod][type][name][arg] -eq -hc -tos 
where eq hc and tos represent options to include equals, hashCode and toString methods. 

Example: python jgen Point -var [pri][i][x] -var [pri][i][y] -mtd [v][setX][[i][x]] -eq -tos

where:
i = int.
d = double.
b = boolean.
v = void.
s = string.
