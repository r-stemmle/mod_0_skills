class Guest

attributes:

name = guests name ("string")
table = guests table # (integer)
number_in_party = number people guest is with (integer)
is_seated = has guest been seated? (boolean)

methods:

change_name() = modifies guests name (changes string)
new_table() = returns the value of the guests table (integer)
add_to_party() = adds number of guests to party (integer)
seat_guest = makes is_seated == true 
