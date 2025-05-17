## bugs fixed

- slow hp bar animation
- off-by-one hp bar animation
- slot machine payout sound effect clipping
- only the first 3 party pokemon will print evolution item compatibility correctly when attempting to use an evolution item from the bag
- Fast Ball only works on 3 pokemon
- Moon Ball only boosts catch rate for pokemon that evolve with Burn Heal
- Heavy Ball uses the incorrect weight value for 3 pokemon
- cathing a transformed pokemon will give the player a ditto
- Burn, Poison, and Paralysis do not increase catch rate
- When an NPC uses a Full Heal, it does not cure confusion or nightmare
- A pokemon holding Berserk Gene will inherit the previous pokemon's confusion counter when it is switched in
- Belly Drum raises attack by 2 stages if it fails
- Moves with an intended guaranteed secondary effect have a 1/256 chance of not triggering them
- Reflect, Light Screen, Metal Powder, Thick Club, and Light Ball cause stats to wrap around when raised above 1024
- Perish Song and Spikes can leave a pokemon with 0 hp and not faint
- Dragon Scale boosts dragon-type moves, not Dragon Fang
- Text during a battle uses a mid-line ellipsis (⋯) instead of the usual ellipsis (…) used everywhere else
- 2 tiles for carpet in the `port` tileset are drawn incorrectly

changes to battle engine make this build incompatible with link battles with vanilla g2 games
<br>
</br>
## changes & new additions
- Berserk Gene confuses for 2-5 turns to match other sources of confusion & its effect in Stadium 2
- Normally a bug, Love ball has been renamed to Gay Ball and its original effect left intact. Its description has been updated
- VICEGRIP has been renamed to VISE GRIP
- the sprite used for boys on the trainer card and during the intro sequence has been switched to the sprite used before in Gold & Silver
- Mr. Mime is now always male
- All held trade evolution items can be used the same way as evolution stones, as well as their original method. This applies to
   - Up-Grade
   - Dragon Scale
   - King's Rock
   - Metal Coat
- All ghost-type moves are now special
- All dark-type moves are now physical
- Crunch lowers defense instead of special defense
- Espeon can evolve by using a Sun Stone or by its original method
- Umbreon can evolve by using a Moon Stone or by its original method
- Phanpy & Donphan can learn Water Gun at Lv:4
