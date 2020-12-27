# Friends Premium

## 1. Commands and Permissions (Party Commands are only for FriendsPremium)

When using BungeeCord, make sure you give the following permissions on BungeeCord!
It does not matter if you are OP or have all permissions on spigot! You will not be able to perform those commands because they are handled trough the proxy and therefor you need these permissions there aswell!

| Commands | Description | Permissions |
| --- | --- | --- |
| /friends add (Name) (Message) | Send a request to a certain player with an optional message | Friends.Commands.Add |
| /friends accept (Name) | Accepts the request from a certain player | Friends.Commands.Accept |
| /friends accept | Accepts the last new request | Friends.Commands.Accept |
| /friends deny (Name) | Denies the request from a certain player | Friends.Commands.Deny |
| /friends deny | Denies the last new request | Friends.Commands.Deny |
| /friends remove (Name) | Removes a player from your friends | Friends.Commands.Remove |
| /friends removeall | Removes all players from your friendlist | Friends.Commands.RemoveAll |
| /friends block (Name) (Note) | Blocks a player with a personal note | Friends.Commands.Block |
| /friends unblock (Name) | Removes a player from your list of blocked players | Friends.Commands.Unblock |
| /friends acceptall | Accepts all open requests | Friends.Commands.AcceptAll |
| /friends denyall | Denies all open requests | Friends.Commands.DenyAll |
| /friends jump (Name) | Jumps to a players server/location | Friends.Commands.Jump
| /friends list | Shows a list of your current friends | Friends.Commands.List |
| /friends status | Shows your current status | - |
| /friends status set (Status) | Change your current status to something new | Friends.Commands.Status.Set |
| /friends status show (Name) | Shows you the status of a certain friend | Friends.Commands.Status.Show |
| /friends msg (Name) (Message) | Send a private message to your friend | Friends.Commands.Msg |
| /msg (Name) (Message) | If enabled, another way to send private messages | Friends.Commands.Msg |
| /friends requests | Toggle wether you want to receive new requests or not | Friends.Commands.Options.Requests |
| /friends messages | Toggle wether you want to receive any kind of message from your friends | Friends.Commands.Options.Messages |
| /friends jumping | Toggle wether you want other players to jump to your location | Friends.Commands.Options.Jumping |
| /friends offlinemode | Toggle wether you want to be shown as offline or online | Friends.Commands.Options.Offline |
| /friends spychat | Enters or leaves the spychat | Friends.Commands.SpyChat |
||||
||||
| /party invite <Name> | Invites an player to your party | Party.Commands.Invite |
| /party accept <Name> | Accepts a requst | Party.Commands.Accept |
| /party deny <Name> | Denies a request | Party.Commands.Deny |
| /party kick <Name> | Removes a player from your party | Party.Commands.Kick |
| /party list | Shows you a list of all players in your party | Party.Commands.List |
| /party promote <Name> | Promotes a party member | Party.Commands.Promote |
| /party demote <Name> | Demotes a partymember | Party.Commands.Demote |
| /party leave | Leaves the party | Party.Commands.Leave |
  
Additional Permissions:

    Friends.FriendLimit.<Number>
        Sets the maximum amount of Friends a player can have. If the players lacks the permission entirely, his limit is set to 0!
    Friends.Status.ChangeLimit.ByPass
        Players with this permission are able to change their status at anytime
    Friends.Commands.Msg.FriendByPass
        Allows a player to send private messages to someone without the need of beeing friends
    Party.Commands.OpenGUI
        Allows the usage of /party to open the PartyGUI ( If enabled in the party.yml )


## 2. Setup (FriendsPremium)

- You need to have a BungeeCord/Waterfall-Network and a MySQL-Database in order to use FriendsPremium!

- Put FriendsPremium on your proxy and the same file on all servers you want the players to use the build-in GUI!
- Restart all servers
- Navigate into the FriendsPremium's newly generated pluginsfolder and open up the MySQL.yml
- Fill in your specifiy login data for your database
- Restart all servers again. You should be good to go.


