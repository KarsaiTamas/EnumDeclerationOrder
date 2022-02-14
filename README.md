# EnumDeclerationOrder
This is something useful which I found on stack overflow. You can get a list of enums in the decleration order.
Or in a custom order which you can set up, see it in the link below.
Original post where I found it: https://stackoverflow.com/a/25147851/11766506
I uploaded it here for easier access.
General usage: EnumExtenstions.GetWithOrder(typeof(enumType))
This gives you a IEnumerable <string>, which you can just use LinQ To turn it into a list.
