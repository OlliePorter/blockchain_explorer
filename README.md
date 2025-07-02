# ⛓️ Blockchain Explorer

A proof of concept Flutter web app for navigating different levels of the [Topl blockchain](https://github.com/Topl). This block explorer is designed to visualize the main levels of the Tetra version of the Topl PoS (Proof-of-Stake) protocol: epochs, blocks and transactions. 


https://user-images.githubusercontent.com/13727615/221472996-f30295f2-9dcd-4db8-b87b-81fe125621ba.mp4


## App Features
This app uses mock block and transaction data from Topl to visualize the layers of the blockchain in a simple, user-friendly UI. Most block explorers in the industry are cumbersome and ugly. They tend to be very dense on data and are not accessible to beginners. The vision of this app is to provide the most minimalistic, easy-to-use gateway to the Topl blockchain. 

Through this block explorer, users can:
- View epochs as grids of blocks (with a breakdown of each block with a block # and other metrics)
- Scroll through epochs horizontally back and forwards in chronological order
- Click on a block to be taken to a level below, which is the view block stacks screen
- Scroll through block stacks horizontally in chronological order
- Click to expand/contract the block stack to view lower-level transactions
- Click on a transaction to see UTXO (unspent transaction output) info

## Prerequisites
This app requires you to have the Flutter SDK installed on your machine. You can follow the instructions for that [here](https://docs.flutter.dev/get-started/install).

## Getting Started
1. Clone down the repo locally
2. Change into the `blockchain_explorer` directory
3. Run the `flutter run -d chrome` to start the app in a Chrome window
