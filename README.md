# Client Config:
- [x] Database : MongoDB
- [x] Rpc : Bantal Store || Ultimate Top-Up & Service Center || Over {itemscount} Transactions Completed

# Commands

## Owner Commands
> Only authorized users from client dev configurations can use these commands.
### Admin Group
- [x] **/admin group create [catalog_name] [group_name] [group_role]** 
  - Create admin group!
- [x] **/admin group modify [group_name] [new_catalog_name] [new_group_name] [group_role]** 
  - Create admin group!
- [x] **/admin group remove [group_name]** 
  - Remove admin group!
### Admin
- [x] **/admin list**
  - Show admins list.
- [x] **/admin info [@user]**
  - Show all information about specified admin.
- [x] **/admin add [@user] [group_name]** 
  - Add an admin to group.
- [x] **/admin remove [@user] [group_name]**
  - Remove an admin from group.
- [x] **/admin delete [@user]** 
  - Delete user from admin.
- [x] **/admin permission [@user] [permission] [state]** 
  - Edit admin permissions.
### Miscellaneous
- [x] **/maintenance [on/off]**
  - Set maintenance mode (all general commands will be disabled, and only authorized users can use the commands if it is on). 

## General Commands
- [ ] **/order [productid] [amount]**
  - make an order
- [x] **/products**
  - show all available products
- [x] **/register [growId]**
  - register growid for deposit
- [x] **/leaderboard**
  - show top 10 spender
- [ ] **/deposit**
  - make deposit
- [x] **/info**
  - show bot information
- [x] **/myinfo**
  - show your information
- [x] **/help**
  - show all bot commands

## Admin Commands

### Edit Channel
- **/channels**
  - Show channels DB.
- **/edit channel set [channel_type] [@channel]**
  - Set channel DB.
- **/edit channel clear**
  - Clear channels DB.

### Edit Assets
- **/assets**
  - Show assets DB.
- **/edit asset set [asset_type] [asset_value]**
  - Set asset DB.
- **/edit asset clear**
  - Clear assets DB.

### Edit Role
- Coming soon [buyer, timeout, cursed, ...]

### Edit Balance
- **/edit balance add [@user] [amount]**
  - Increase a user's balance by the specified amount.
- **/edit balance sub [@user] [amount]**
  - Decrease a user's balance by the specified amount.
- **/edit balance set [@user] [amount]**
  - Set a user's balance to the specified amount.

### Edit Catalog
- **/edit catalog create [catalog_name] [catalog_emoji]**
  - Create a new catalog with the specified name and emoji.
- **/edit catalog modify [catalog_name] [new_catalog_name] [new_catalog_emoji?]**
  - Modify an existing catalog's name and optionally its emoji.
- **/edit catalog remove [catalog_name]**
  - Remove an existing catalog.

### Edit Category
- **/edit category create [catalog_name] [category_name]**
  - Create a new category within the specified catalog.
- **/edit category modify [category_name] [new_category_name]**
  - Change the name of an existing category.
- **/edit category remove [category_name]**
  - Delete a category from a catalog.

### Edit Product
- **/edit product create [category_name] [product_id] [product_price] [product_description]**
  - Add a new product to a category with specified details.
- **/edit product modify [product_id] [new_product_id] [new_product_price] [new_product_description]**
  - Update the details of an existing product.
- **/edit product remove [product_id]**
  - Delete a product from a category.

### Edit Stock
- **/edit stock push [product_id] [product_data_file?] [product_data?]**
  - Add stock to a product using a data file or direct data input.
- **/edit stock clear [product_id]**
  - Clear all stock data for a product.
- **/edit stock remove [product_id] [stock_data]**
  - Remove specific stock data from a product.
- **/edit stock pull [product_id] [amount]**
  - Retrieve and send the specified amount of stock data.

### Miscellaneous
- **/userinfo [@user]**
  - Display information about a user.
- **/prefix [prefix]**
  - Change the command prefix for the bot.
- [ ] **/shop settings**
  - easy setup
- [ ] **/embed**
  - Embed creator, generated embed can be used in some commands!

#########
- [ ] Setdeposit
- [ ] Setup (buat check bot ready digunakan atau belum)
- [ ] showasset
- [ ] ban (banned + kata katain di general)
- [ ] deploymenu
- [ ] deployleaderboard
- [ ] givestock
- [ ] edit
- [ ] setprice
- [ ] setuser
- [ ] [showassets](https://discord.com/channels/1036152375091671140/1268954498542600388/1268959033239539763)
- [ ] stopmenu
- [ ] stopleaderboard

## Requested:
- [ ] deploymenu // ini bisa kaya takutnya kedepannya ga df doang kan jadi aku pengen, /deploymenu codeid:1
  - [ ] dia replies what u add text on text bla2 nya itu udah dikirim sama pengirim (limit 10menit kalo ga kedetek 10 menit jawab dia cancel)
  - [ ] terus replies lagi using embed? yes (embed format nanti dikasi)
  - [ ] terus replies lagi using bannerembed? linkbannerassets
  - [ ] terus replies lagi using buttonmenu? yes (buttonnya text :EmoteLucu: Bantal Store Menu :EmoteLucu:) pass di pencet ada
    - [ ] 1. Check User
    - [ ] 2. Show Product
    - [ ] 3. Order
    - [ ] kalo Pencet Check User itu dibawahnya ada tombol dam kaya ke belakang sama kedepan + tombol refresh kaya breadbumb apalah namanya tu yg page 1 2 3
- [ ] deploymenuedit // codeid:1 munculin embed preview dengan button dibawah ada
  - [ ] 1. Edit Text
  - [ ] 2. Edit Embed
  - [ ] 3. Edit BannerEmbed
- [ ] deploymenudelete // codeid:1
- [ ] chartsold adminlist:(masing2 admin bisa check perday sold & bisa misal alladmin) day:1-30  /// Apexchart keanya
- [ ] checksold adminlist:(masing2 admin bisa check  & bisa alladmin)
  - [ ] formatnya kalo alladmin Embed
    - [ ] # Admin Stock List
      - [ ] @NameAdmin - Stock : 11 - Sold : 5 - 200 :Wls:
      - [ ] Paling Bawah tambahin
        - [ ] World Claim : {world}
  - [ ] formatnya kalo masing2 admin kaya info balance aja paling gantiin GrowID jadi Admin Name/id ngetag terus Balancenya ganti jadi Sold Count
    - [ ] terus Total Spendnya ganti jadi Total Balance (Balance : Sold Wls)
    - [ ] Paling Bawah tambahin
      - [ ] World Claim : {world}
- [ ] claimsold adminlist:(masing2 admin) take:(optional(nguranginwls)) // clear sold list dari fitur checksold
- [ ] editclaim {worldclaim}
- [ ] customize promo

#### Note:
