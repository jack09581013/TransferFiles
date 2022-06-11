## Pause Methods
```shell
# Pause Method 1
function pause(){
	read -s -n 1 -p "Press any key to continue . . ."
	echo ""
}
 
# Pause it
pause

# Pause Method 2
read -p "Press any key to continue..."

p prompt
	output the string PROMPT without a trailing newline before attempting to read	