# PythonEVERYDAY
Collects Python articles from various Sources
NAMESPACE
Name (which means name, a unique identifier) + Space(which talks something related to scope). Here, a name might be of any Python method or variable and space depends upon the location from where is trying to access a variable or a method.

# a is in the global namespace
a = 5
def some_func():

	# b is in the local namespace
	b = 6
	def some_inner_func():

		# c is in the nested local
		# namespace
		c = 7
