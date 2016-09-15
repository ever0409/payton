@bot.message_handler(commands=['nitro'])
def nitro(m):
    cid = m.chat.id
    markup = types.InlineKeyboardMarkup()
    ret_msg = bot.send_message(cid, "Write Soon ```{}```", disable_notification=True, reply_markup=markup)
    assert ret_msg.message_id
