# Discord-Moderation-bot
   Basic discord bot written in python and discord.py to provide useful moderation tools to a discord server

# Features
   - kick
   - Ban/unban/softban
   - Clear
   - Mute/unmute (in progress)
   - status change (in progress)
   - moderation logs (in progress)
 
# How to setup
   To setup this bot yourself simply clone the repo add the token from the discord bot bot you have created via discord:
   
   ```
   bot.run('insert_token_here')
   ```
    
   To change the command prefix (default = './') to something such as "/" or "~":
   ```
   bot = commands.Bot(command_prefix = 'insert_preifx_here')
   ```
   
# How to use
   Commands:
   - Kick: ./kick member_name
   - Ban: ./ban  member_name
   - Unban: ./unban member_name
   - Softban: ./softban member_name time
   - Clear: ./clear 20 (this means 20 messages will be deleted)
