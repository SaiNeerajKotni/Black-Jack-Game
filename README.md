# 🃏 Blackjack - A Python Game 🎲

## 🎯 About

This is a simple **text-based Blackjack game** built in Python. It allows players to:\
✔ Place bets using virtual chips.\
✔ Draw cards and try to get as close to **21** as possible without busting.\
✔ Choose to **Hit, Stand, or Double Down**.\
✔ Play against a dealer that follows the **stand-on-17** rule.

## 🚀 Features

✅ Betting System with Virtual Chips 💰\
✅ Dealer follows the **Blackjack Rules** 🏆\
✅ Supports **Hit, Stand, and Double Down** options 🎯\
✅ Play multiple rounds until you run out of chips 🔄

## 📌 How to play
1️⃣ Run the script:
2️⃣ Enter the number of chips you want to start with.
3️⃣ Place your bet and play!
4️⃣ Choose to Hit, Stand, or Double Down.
5️⃣ Try to beat the dealer without going over 21.

 ## 🛠 Future Improvements
🔹 Implement Splitting Pairs
🔹 Improve Dealer AI 🤖
🔹 Create a GUI Version using Tkinter or Pygame


## Key Changes in the Blackjack Game:

## 🃎 Ace Adjustment for Better Hand Calculation:
Implemented logic to dynamically adjust Ace's value from 11 to 1 if the total exceeds 21, preventing unnecessary busts and improving hand flexibility.

## 🎯 Bust Handling Enhanced:
Player’s turn now ends immediately after busting, with a clear message.
Bust logic now integrates smoothly with Ace adjustments.

## 💵 Double Bet Logic Fixed:
The bet amount now doubles correctly when the player chooses 'double'.
Loss after doubling reflects the correct doubled amount.

## 🎲 Payout Consistency:
Corrected final winnings calculations, including Blackjack payouts (3:2), ties, and bust losses.
Accurate chip tracking after each round.

## 🃏 Dealer Logic Refined:
Dealer stands at 17 or higher.
Proper handling of dealer bust scenarios with appropriate player payouts.

## 📜 License
This project is open-source and available under the MIT License.

## 🤝 Contributing
Feel free to fork the repo, create an issue, or submit a pull request if you want to improve the game!

Happy playing! 🃏✨
