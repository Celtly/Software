thing_wrong := *.o # Don't do this! '*' will not get expanded
thing_right := $(wildcart *.o)

all: one two three

# Failes, because $(thing_wrong) is the string "*.o"
one: $(thing_wrong)

# Starys as *.o if there are no files that match this pattern :(
two: *.o

# works as you would hope it did! In this case, it does nothing
three: $(thing_right)

# same as rule three
four: $(wildcart *.o)
