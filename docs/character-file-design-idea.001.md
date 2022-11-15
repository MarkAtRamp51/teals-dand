# A D & D Character File Prototype 001

The character file needs the necessary attributes to allow for battle

The character file needs descriptive attributes to make the game interesting and fun.  Like character name "Battle Girl", favorite saying "Come get me Bro!"

The gameStats would be computed by the server and send back to the python client program to be merged into th eplayer file.  The signature verifies the authenticity of the gameStates and the battleTraits.  So when the character is sent back to the server if the signature doesn't validate it can send it back to the player, and they can choose to pick a new character file or have the server ignore the invalid gameStats.  Game states would be invalid if you altered anything in battleTraits or gameStats manually, once a gameStats had been calculated.

***Mason***, personality cna contain anything and be modified any time.  battleTraits I think should be things that influence battle outcomes, let me know what you think should be in there.  Which would be governed by the character creator you are building with the kids.


```json
{
    "battleTraits":
    {

    },
    "personality":
    {

    },
    "gameStats":
    {
        "level": 0,
        "experience": 0,
        "signature":"973429674289349hfghaskjgfskgf89wgh3rwbfhklsnf3=",
        "matchStats": {
            "totals": {
                "wins":0,
                "loss":0,
                "draw":0
            },
            "classStats": {
                "wizard": {
                    "wins":0,
                    "loss":0,
                    "draw":0
                },
                "barbarian": {
                    "wins":0,
                    "loss":0,
                    "draw":0
                },
                "paladin": {
                    "wins":0,
                    "loss":0,
                    "draw":0
                },
                "bard": {
                    "wins":0,
                    "loss":0,
                    "draw":0
                },                                                
            },
            "playerStats": {
                "thomas": {
                    "wins":0,
                    "loss":0,
                    "draw":0
                },
                "breckan": {
                    "wins":0,
                    "loss":0,
                    "draw":0
                },
            }
        }
    }
}
```