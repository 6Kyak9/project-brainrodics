import telebot

bot = telebot.TeleBot("token")

@bot.message_handler(commands=['start'])
def start(message):
    bot.send_message(message.chat.id, 'Я на связи. Напиши мне что-нибудь, и я отвечу)')

bot.polling(none_stop=True)
