# Client Config:
- [x] Database : MongoDB
- [x] Rpc : Bantal Store || Ultimate Top-Up & Service Center || Over {itemscount} Transactions Completed

# Commands

## Owner Commands
> Only authorized users from client dev configurations can use these commands.
- [x] **/maintenance [on/off]**
  - Set maintenance mode (all commands will be disabled, and only authorized users can use the commands if it is on). 
- [ ] **/admin list**
  - Show admin lists.
- [ ] **/admin add [@user]** 
  - Add an admin.
- [ ] **/admin remove [@user]** 
  - Remove an admin.

## General Commands
- [ ] **/order [productid] [amount]**
  - make an order
- [ ] **/products**
  - show all available products
- [ ] **/register [growId]**
  - register growid for deposit
- [ ] **/leaderboard**
  - show top 10 leaderboard
- [ ] **/deposit**
  - make deposit
- [ ] **/info**
  - show bot information
- [ ] **/help**
  - show all bot commands

## Admin Commands

- [ ] **/balance add [@user] [type] [amount]**
  - add user balance
- [ ] **/balance sub [@user] [type] [amount]**
  - substract user balance
- [ ] **/balance set [@user] [type] [amount]**
  - set user balance


- [ ] Addstock (Bisa Optional Attachfile/not kalo bisa kalo ngga bisa langsung attachfile aj)
- [ ] Addassets (Add Template Database)
- [ ] Changeassets
- [ ] Setchannelhistory
- [ ] Setdeposit
- [ ] Setorderstate (mau disable order atau ngga/ maintenance system)
- [ ] Setup (buat check bot ready digunakan atau belum)
- [ ] [Checkuser](https://discord.com/channels/1036152375091671140/1268954498542600388/1268954790927405149) (check user like saldo join ke server kapan (udah di server itu berapa lama) terus ada info dia spent berapa)
- [ ] setwebhookfail // webhook fail donate add balance
- [ ] setwebhooksold // webhook tiap kejual infoin stock siapa2 nya
- [ ] showasset
- [ ] ban (banned + kata katain di general)
- [ ] deploymenu
- [ ] deployleaderboard
- [ ] addproduk
- [ ] removeproduct
- [ ] givestock
- [ ] givecurrency
- [ ] edit
- [ ] setprice
- [ ] setuser
- [ ] showassets (Emote DB & Banner Assets)
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
