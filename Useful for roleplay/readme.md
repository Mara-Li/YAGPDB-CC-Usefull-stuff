This function delete the "HRP" - text starting with `(` - in some category.

# FIRST : Configure `rmc.yag`
   
**Command and usage** : `$rmc <category ID>` 

You can :
- Use it in a channel, with only `$rmc`. It will add the category linked to the channel where you use the command
- Add directly a list of category ID
- Add one category.

# SECOND : Add the `deleteHRP.yag`

After, you must add the `deleteHRP.yag` like that :
   - **Trigger** : `regex` with : `^\((.*)?\)?`
   - Usage : After 180 seconds (3min), it will delete the HRP in the category. 

⚠ It not work on edited message and bot. 
