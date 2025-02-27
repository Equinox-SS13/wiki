---
title: Guide to Cargo
description: Trading, money making, and tax evading.
published: true
date: 2025-02-27T03:21:51.041Z
tags: guide, cargo, other guide, wiki: stub, cargo guide
editor: markdown
dateCreated: 2024-08-29T09:04:45.912Z
---

> [**Stub**](/maintenance/Templates#stub): This article or section is **incomplete** and require more write up or expansion on the content. **Reason**: `reasonhere`
{.is-danger}

# Cargo / Trading
Welcome to Cargo! You're the colony's primary source of materials, the driver of its economy - the primary money sink and the primary money generator, and the main source of materials with the miners under the same department.

This guide assume you're a Cargo Technician / Manager, or a miner who has been granted access to the departmental account (Or an enterprising solo miner), and teach you about the trading part of the cargo department.

## Trading Program
Your job revolves around the Trading Program, which can be accessed by any console or laptop that has sufficient access. Conveniently, the cargo bay area start off with one console with the trading program pre-loaded in the middle (On the cursor): 

![cargobayscreenshot1.png](/cargoguide/cargobayscreenshot1.png)

In the same screenshot, you can see:
- The receiving beacon - where incoming goods will land (Marked with yellow)
- The sending beacon - where outgoing goods / export will be placed
- The console - which is the most convenient spot to do all of your trading and come with the Trading Program pre loaded
- The autolathe, alongside starting disk(s), this is important for Cargo to produce various goods on request for export

To get started, head to the console and click on it. The Trading Program should be preloaded, but if it is not, look for "Trading Program". You will be greeted with the following interface:

![tradingprogram.png](/cargoguide/tradingprogram.png)

You can get started with the following steps:
1. Click on Account, enter an Account Number and then the Pin - If you're a Manager / Cargo Tech, you should have access to your department's account. (Nothing stops you from using your own, or any other accounts you have the account number & pin combination for however!). You can press X to log out.
2. Click on both Receiving Beacon and Sending Beacon. If your console is close enough to the sending and receiving beacon, it will be automatically linked!

From this point on, purchase will be made using funds from the account and any profits made from offers or exports will be credited to that account. The linked receiving & sending beacon will be where the incoming / outgoing goods go. 

On the bottom of the interface, you can see various green squares and red squares with white lines linking them together. You can hover over them to see their names:
- Green Squares are unlocked traders you can trade with
- Red Squares are locked traders you can trade with
- White Lines indicates that you can unlock this trader by getting 1 or more recommendations from the traders above them - more on this later!

To get started, click on one of the trader and then click "To Trade Screen" - if you want to get back to this screen and switch to another trader, you can click "To Merchants".

### Import, Export, Goods & Offers
![refinerytrader.png](/cargoguide/refinerytrader.png)

On the Trade Screen, you can see the current merchant you have selected. Each merchant has a category of **Goods** - which it will buy or sell from you, and **Offers**, which they will buy from you, usually for a hefty profit.

To purchase goods you want, click on the "+" button, which will add it to your current Cart - the list of items you will purchase but has not finalized yet. "-" will reduce the amount of goods you have in your cart. "Price" is the price that you will purchase the goods at, "Available" indicates the amount of stock this trader have, and "Sell Price" is the money you can get if you sold this item to the trader.

On the bottom left, you can see "Cart:" with a cart button underneath it that indicates the total cost of your current order. "Reset" allows you to reset your entire order, and "View Cart" let you view your entire order. You do not need to stick to a single trader and can switch between different trader before finalizing your transaction by clicking on the Cart button with your total cost.

Once you do so, the appropriate amount will be charged to the linked account, and your shiny new goods will arrive in a single crate on the **Receiving Beacon** (regardless of how much you've ordered!).

All trader will buy back the goods they sell to you. However, items that are bought by a trader will often have a "Surplus" tag attached to them, allowing you to only sell back for a tenth of the normal price. To sell (back) the goods, you can click on the basket-like button next to the good. The item must be on the **Sending Beacon** for you to sell it.

You can also see "Offer Time" on the top of the interface. This is a timer - globally shared across all traders for when they will restock and when they will refresh their Offers - which we'll get to a moment.

#### Offers
Offers is the primary way you make money through the trading system. To see what offer an individual merchant has, click on the "Offers" tab: 

![tradeoffer.png](/cargoguide/tradeoffer.png)

You can see here that the trader Recoll is purchasing full stack of materials and modified tools and scrap metals. To fulfill these offers, put down the items they ask for on the **Sending Beacon**, then click on "Send" at the console to sell it to them.

Under "Amount" is two number. On the left is the amount of qualifying items you have on the Sending Beacon, on the right is the **minimum amount** required to fulfill the order. You must have at least that amount of goods on the sending beacon for the offer to count. Each offer can only be fulfilled once per cycle.

Some notes about the offers system:
- When it comes to stack, a full stack is required - any less will not count. The same goes for medicine.
- Modified X means the total number of upgrades on the pickaxe / shovel
- Some item, such as meat, will also count any of the subtypes of said item - such as the far more valuable roach meat or even kaiser meat (!). You will want to be careful and make sure you fulfill the more valuable offers first - such as offers for Kaiser meat instead of normal meat, or move the more valuable meats off the pad
- Conversely, you may not always need the exact items the names state to fulfill an order - sub type of that item may also be fulfilled

## Trader Mechanics
There's some detailed trader mechanics you will want to be aware of. 

The first is "Favor". Favor is shown as 0 / Maximum Favor. Favor has two purposes - it unlocks the hidden inventory of the trader, and it allows a trader to recommend you to the next trader in line, potentially unlocking them. 

Currently, the hidden inventory and recommendation threshold are different on all traders, and completely inconsistent across all of the traders. The maximum favor display the highest of the either and the only way to know which is which is to dive into code (Do not do that and simply unlock the maximum favor for now!).

To unlock a trader, you will need to obtain enough recommendations from the merchant above them - each trader will recommends you to a set number of merchant as indicated by the dotted line. How many recommendations is needed to unlock a merchant is unfortunately a hidden mechanic as not yet unlocked traders cannot be clicked yet. Generally speaking you can always expect to unlock the next trader in a straight line, whereas trader with multiple lines leading to them often require more than one.

## Other Trading Program Mechanics

### View Cart / Cart
![viewcart.png](/cargoguide/viewcart.png)

When you click "View Cart", you can view all of the items you have in your cart across all of your traders.

You can Save and Load your Cart - which are saved on a program level to reuse orders you may want to repeat later. (No clue what happens if they're out of stock - add later)

By clicking on "Create Order", and then entering a Reason for the order, you can create an Order Request which can be fulfilled by Cargo - as a Cargo member this is probably not useful, but as other departments it is a convenient way to order something quickly!

### Order Request
![orderrequest.png](/cargoguide/orderrequest.png)

The order request menu let you see any pending Order Request from other people requested by another console - or more likely the Trade Order Requests app on their PDA. 

You can hover over "View" to see what is in the order, "View Orders" in order to put the full order with reason at the top of your screen, Purchase to purchase the order, Deny to deny it, and Save to save the content in a cart of your own. 

If the purchaser is the Cargo Account, there'll be no handling fee (Although there's usually no reason to do so). Otherwise an additional default handling fee of 20% will be charged to the account that purchased the goods - Only the account that requested the trade order will be charged. The handling fee will be credited to the departmental account. 

It is generally a good idea to deliver the goods to your customer or ask for them to pick it up after purchasing with their account's money.

## General Trading Tips

## Phone of Cheating



## Trade Partners

## Request Fulfillment

