# -
from asyncio import sleep @bot.event async def on_ready():      while True:           await bot.change_presence(status=discord.Status.online, activity=discord.Game("Текст игры"))           await sleep(15)           await bot.change_presence(status=discord.Status.online,activity=discord.Streaming("Текст стрима"))           await sleep(15)
