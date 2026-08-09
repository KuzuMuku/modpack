# OneEnoughDamage 未归属伤害点汇总

以下伤害点无法追溯到某个 LivingEntity。每个条目标注了其最终来源类型（物品、弹射物、方块、效果等），运行时通常通过 Projectile Base Damage 或其他全局机制生效。

This file lists scanned configurable hardcoded damage attributes by namespace and source.
`/r` means replace original damage directly, `/m` means multiply original damage.

## Aether

### AbstractDart (Type: Projectile)

- `oneenoughdamage:com/aetherteam/aether/entity/projectile/dart/abstract_dart/m_5790/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: unknown, com.aetherteam.aether.entity.projectile.dart.AbstractDart#m_5790_#1 -->

### CollideGoal (Type: Other)

- `oneenoughdamage:com/aetherteam/aether/entity/monster/dungeon/boss/goal/collide_goal/m_8037/1/r` <!-- mode: replace (/r), default: 6.0, DamageType: aetherdamagetypes:entity_damage_source, com.aetherteam.aether.entity.monster.dungeon.boss.goal.CollideGoal#m_8037_#1 -->

### Floating Block (悬浮方块) (Type: Block)

- `oneenoughdamage:com/aetherteam/aether/entity/block/floating_block_entity/lambda_cause_fall_damage_0/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: unknown, com.aetherteam.aether.entity.block.FloatingBlockEntity#lambda$causeFallDamage$0#1 -->

### Hammer Projectile (创世者锤头) (Type: Projectile)

- `oneenoughdamage:com/aetherteam/aether/entity/projectile/weapon/hammer_projectile/launch_target/1/r` <!-- mode: replace (/r), default: 7.0, DamageType: m_269390, com.aetherteam.aether.entity.projectile.weapon.HammerProjectile#launchTarget#1 -->

### InebriationEffect (Type: Effect)

- `oneenoughdamage:com/aetherteam/aether/effect/inebriation_effect/m_6742/1/r` <!-- mode: replace (/r), default: 1.0, DamageType: aetherdamagetypes:damage_source, com.aetherteam.aether.effect.InebriationEffect#m_6742_#1 -->

## Aetherdelight

### ZaniteKnifeLivingEntityIsHitWithToolProcedure (Type: Other)

- `oneenoughdamage:net/mcreator/aetherdelight/procedures/zanite_knife_living_entity_is_hit_with_tool_procedure/execute/1/r` <!-- mode: replace (/r), default: 3.0, DamageType: unknown, net.mcreator.aetherdelight.procedures.ZaniteKnifeLivingEntityIsHitWithToolProcedure#execute#1 -->

## Alexsmobs

### BlueJayAIMelee (Type: Other)

- `oneenoughdamage:com/github/alexthe666/alexsmobs/entity/ai/blue_jay_a_i_melee/m_8037/1/r` <!-- mode: replace (/r), default: 1.0, DamageType: m_269264, com.github.alexthe666.alexsmobs.entity.ai.BlueJayAIMelee#m_8037_#1 -->

### BunfungusAIMelee (Type: Other)

- `oneenoughdamage:com/github/alexthe666/alexsmobs/entity/ai/bunfungus_a_i_melee/m_8037/1/r` <!-- mode: replace (/r), default: 10.0, DamageType: m_269333, com.github.alexthe666.alexsmobs.entity.ai.BunfungusAIMelee#m_8037_#1 -->

### CaimanAIMelee (Type: Other)

- `oneenoughdamage:com/github/alexthe666/alexsmobs/entity/ai/caiman_a_i_melee/m_8037/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: m_269333, com.github.alexthe666.alexsmobs.entity.ai.CaimanAIMelee#m_8037_#1 -->

### CrowAIMelee (Type: Other)

- `oneenoughdamage:com/github/alexthe666/alexsmobs/entity/ai/crow_a_i_melee/m_8037/1/r` <!-- mode: replace (/r), default: 4.0, DamageType: m_269264, com.github.alexthe666.alexsmobs.entity.ai.CrowAIMelee#m_8037_#1 -->
- `oneenoughdamage:com/github/alexthe666/alexsmobs/entity/ai/crow_a_i_melee/m_8037/2/r` <!-- mode: replace (/r), default: 1.0, DamageType: m_269264, com.github.alexthe666.alexsmobs.entity.ai.CrowAIMelee#m_8037_#2 -->

### Debilitating Sting (Type: Effect)

- `oneenoughdamage:com/github/alexthe666/alexsmobs/effect/effect_debilitating_sting/m_6742/1/r` <!-- mode: replace (/r), default: 1.0, DamageType: m_269425, com.github.alexthe666.alexsmobs.effect.EffectDebilitatingSting#m_6742_#1 -->
- `oneenoughdamage:com/github/alexthe666/alexsmobs/effect/effect_debilitating_sting/m_6742/2/m` <!-- mode: multiply (/m), default: 1.0, DamageType: m_269425, com.github.alexthe666.alexsmobs.effect.EffectDebilitatingSting#m_6742_#2 -->

### Ender Flu (Type: Effect)

- `oneenoughdamage:com/github/alexthe666/alexsmobs/effect/effect_ender_flu/m_6742/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: m_269425, com.github.alexthe666.alexsmobs.effect.EffectEnderFlu#m_6742_#1 -->

### EntityMobProjectile (Type: Entity)

- `oneenoughdamage:com/github/alexthe666/alexsmobs/entity/entity_mob_projectile/on_entity_hit/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: m_269299, com.github.alexthe666.alexsmobs.entity.EntityMobProjectile#onEntityHit#1 -->

### EntitySharkToothArrow (Type: Projectile)

- `oneenoughdamage:com/github/alexthe666/alexsmobs/entity/entity_shark_tooth_arrow/m_7761/1/r` <!-- mode: replace (/r), default: 7.0, DamageType: m_269418, com.github.alexthe666.alexsmobs.entity.EntitySharkToothArrow#m_7761_#1 -->

### EntityTendonSegment (Type: Entity)

- `oneenoughdamage:com/github/alexthe666/alexsmobs/entity/entity_tendon_segment/m_8119/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: m_269299, com.github.alexthe666.alexsmobs.entity.EntityTendonSegment#m_8119_#1 -->

### Exsanguination (Type: Effect)

- `oneenoughdamage:com/github/alexthe666/alexsmobs/effect/effect_exsanguination/m_6742/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: m_269425, com.github.alexthe666.alexsmobs.effect.EffectExsanguination#m_6742_#1 -->

### FroststalkerAIMelee (Type: Other)

- `oneenoughdamage:com/github/alexthe666/alexsmobs/entity/ai/froststalker_a_i_melee/m_8037/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: m_269333, com.github.alexthe666.alexsmobs.entity.ai.FroststalkerAIMelee#m_8037_#1 -->

### GrizzlyBearAIAprilFools (Type: Other)

- `oneenoughdamage:com/github/alexthe666/alexsmobs/entity/ai/grizzly_bear_a_i_april_fools/m_8037/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: amdamagetypes:cause_freddy_bear_damage, com.github.alexthe666.alexsmobs.entity.ai.GrizzlyBearAIAprilFools#m_8037_#1 -->
- `oneenoughdamage:com/github/alexthe666/alexsmobs/entity/ai/grizzly_bear_a_i_april_fools/m_8037/2/m` <!-- mode: multiply (/m), default: 1.0, DamageType: amdamagetypes:cause_freddy_bear_damage, com.github.alexthe666.alexsmobs.entity.ai.GrizzlyBearAIAprilFools#m_8037_#2 -->

### MessageHurtMultipart (Type: Other)

- `oneenoughdamage:com/github/alexthe666/alexsmobs/message/message_hurt_multipart_handler/lambda_handle_0/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: unknown, com.github.alexthe666.alexsmobs.message.MessageHurtMultipart$Handler#lambda$handle$0#1 -->

### RockyChestplateUtil (Type: Other)

- `oneenoughdamage:com/github/alexthe666/alexsmobs/entity/util/rocky_chestplate_util/tick_rocky_rolling/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: m_269333, com.github.alexthe666.alexsmobs.entity.util.RockyChestplateUtil#tickRockyRolling#1 -->

### ServerEvents (Type: Other)

- `oneenoughdamage:com/github/alexthe666/alexsmobs/event/server_events/on_living_damage_event/1/r` <!-- mode: replace (/r), default: 1.0, DamageType: m_269374, com.github.alexthe666.alexsmobs.event.ServerEvents#onLivingDamageEvent#1 -->

### SnowLeopardAIMelee (Type: Other)

- `oneenoughdamage:com/github/alexthe666/alexsmobs/entity/ai/snow_leopard_a_i_melee/m_8037/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: m_269333, com.github.alexthe666.alexsmobs.entity.ai.SnowLeopardAIMelee#m_8037_#1 -->

### TileEntitySculkBoomer (Type: Other)

- `oneenoughdamage:com/github/alexthe666/alexsmobs/tileentity/tile_entity_sculk_boomer/common_tick/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: m_269425, com.github.alexthe666.alexsmobs.tileentity.TileEntitySculkBoomer#commonTick#1 -->

### TileEntityVoidWormBeak (Type: Other)

- `oneenoughdamage:com/github/alexthe666/alexsmobs/tileentity/tile_entity_void_worm_beak/tick/1/r` <!-- mode: replace (/r), default: 5.0, DamageType: m_269264, com.github.alexthe666.alexsmobs.tileentity.TileEntityVoidWormBeak#tick#1 -->

## Amendments

### CommonCauldronCode (Type: Other)

- `oneenoughdamage:net/mehvahdjukaar/amendments/common/block/common_cauldron_code/entity_inside/1/r` <!-- mode: replace (/r), default: 1.0, DamageType: unknown, net.mehvahdjukaar.amendments.common.block.CommonCauldronCode#entityInside#1 -->

### Dragon Fireball (龙弹火球) (Type: Projectile)

- `oneenoughdamage:net/mehvahdjukaar/amendments/common/entity/medium_dragon_fireball/m_5790/1/r` <!-- mode: replace (/r), default: 2.0, DamageType: m_269104, net.mehvahdjukaar.amendments.common.entity.MediumDragonFireball#m_5790_#1 -->

### Fireball (火球) (Type: Projectile)

- `oneenoughdamage:net/mehvahdjukaar/amendments/common/entity/medium_fireball/m_5790/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: mediumfireball:fireball_damage, net.mehvahdjukaar.amendments.common.entity.MediumFireball#m_5790_#1 -->
- `oneenoughdamage:net/mehvahdjukaar/amendments/common/entity/medium_fireball/m_5790/2/m` <!-- mode: multiply (/m), default: 1.0, DamageType: mediumfireball:fireball_damage, net.mehvahdjukaar.amendments.common.entity.MediumFireball#m_5790_#2 -->

### FireballExplosion (Type: Other)

- `oneenoughdamage:net/mehvahdjukaar/amendments/common/entity/fireball_explosion/hurt_hit_entity/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: unknown, net.mehvahdjukaar.amendments.common.entity.FireballExplosion#hurtHitEntity#1 -->

## Antarcticgardens

### RadiationPoisoningEffect (Type: Effect)

- `oneenoughdamage:org/antarcticgardens/cna/content/nuclear/radiation_poisoning_effect/m_6742/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: m_269425, org.antarcticgardens.cna.content.nuclear.RadiationPoisoningEffect#m_6742_#1 -->

## Appeng

### ChargedStaffItem (Type: Item)

- `oneenoughdamage:appeng/items/tools/powered/charged_staff_item/m_7579/1/r` <!-- mode: replace (/r), default: 6.0, DamageType: m_269425, appeng.items.tools.powered.ChargedStaffItem#m_7579_#1 -->

### MatterCannonItem (Type: Item)

- `oneenoughdamage:appeng/items/tools/powered/matter_cannon_item/shoot_paint_balls/1/r` <!-- mode: replace (/r), default: 0.0, DamageType: m_269075, appeng.items.tools.powered.MatterCannonItem#shootPaintBalls#1 -->
- `oneenoughdamage:appeng/items/tools/powered/matter_cannon_item/standard_ammo/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: unknown, appeng.items.tools.powered.MatterCannonItem#standardAmmo#1 -->
- `oneenoughdamage:appeng/items/tools/powered/matter_cannon_item/standard_ammo/2/m` <!-- mode: multiply (/m), default: 1.0, DamageType: unknown, appeng.items.tools.powered.MatterCannonItem#standardAmmo#2 -->

### TinyTNTPrimedEntity (Type: Entity)

- `oneenoughdamage:appeng/entity/tiny_t_n_t_primed_entity/m_32103/1/r` <!-- mode: replace (/r), default: 6.0, DamageType: m_269093, appeng.entity.TinyTNTPrimedEntity#m_32103_#1 -->

## Aquamirae

### CrystallizationMobEffect (Type: Effect)

- `oneenoughdamage:com/obscuria/aquamirae/common/effects/crystallization_mob_effect/m_6386/1/r` <!-- mode: replace (/r), default: 999999.0, DamageType: unknown, com.obscuria.aquamirae.common.effects.CrystallizationMobEffect#m_6386_#1 -->

### SharpBonesItem (Type: Item)

- `oneenoughdamage:com/obscuria/aquamirae/common/items/sharp_bones_item/m_5922/1/r` <!-- mode: replace (/r), default: 1.0, DamageType: m_269064, com.obscuria.aquamirae.common.items.SharpBonesItem#m_5922_#1 -->

### TerribleSwordItem (Type: Item)

- `oneenoughdamage:com/obscuria/aquamirae/common/items/weapon/terrible_sword_item/lambda_new_0/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: m_269254, com.obscuria.aquamirae.common.items.weapon.TerribleSwordItem#lambda$new$0#1 -->

## Ars Nouveau

### Enchanter's Bow (巫师之弓) (Type: Item)

- `oneenoughdamage:com/hollingsworth/arsnouveau/common/entity/entity_spell_arrow/m_5790/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: unknown, com.hollingsworth.arsnouveau.common.entity.EntitySpellArrow#m_5790_#1 -->

### Enchanter's Crossbow (巫师之弩) (Type: Item)

- `oneenoughdamage:com/hollingsworth/arsnouveau/common/entity/entity_spell_arrow/m_5790/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: unknown, com.hollingsworth.arsnouveau.common.entity.EntitySpellArrow#m_5790_#1 -->
- `oneenoughdamage:net/minecraft/world/entity/projectile/firework_rocket_entity/m_37087/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: m_268994, net.minecraft.world.entity.projectile.FireworkRocketEntity#m_37087_#1 -->
- `oneenoughdamage:net/minecraft/world/entity/projectile/firework_rocket_entity/m_37087/2/m` <!-- mode: multiply (/m), default: 1.0, DamageType: m_268994, net.minecraft.world.entity.projectile.FireworkRocketEntity#m_37087_#2 -->

### Fangs (牙) (Type: Other)

- `oneenoughdamage:com/hollingsworth/arsnouveau/common/entity/entity_evoker_fangs/damage/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: m_269425, com.hollingsworth.arsnouveau.common.entity.EntityEvokerFangs#damage#1 -->
- `oneenoughdamage:com/hollingsworth/arsnouveau/common/entity/entity_evoker_fangs/damage/2/m` <!-- mode: multiply (/m), default: 1.0, DamageType: m_269104, com.hollingsworth.arsnouveau.common.entity.EntityEvokerFangs#damage#2 -->

### Spell Arrow (法术之箭) (Type: Item)

- `oneenoughdamage:com/hollingsworth/arsnouveau/common/entity/entity_spell_arrow/m_5790/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: unknown, com.hollingsworth.arsnouveau.common.entity.EntitySpellArrow#m_5790_#1 -->

## Bosses Of Mass Destruction

### BurstAction (Type: Other)

- `oneenoughdamage:com/cerbon/bosses_of_mass_destruction/entity/custom/obsidilith/burst_action/damage_entity/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: unknown, com.cerbon.bosses_of_mass_destruction.entity.custom.obsidilith.BurstAction#damageEntity#1 -->

### ChargedEnderPearlEntity (Type: Projectile)

- `oneenoughdamage:com/cerbon/bosses_of_mass_destruction/item/custom/charged_ender_pearl_entity/m_5790/1/r` <!-- mode: replace (/r), default: 0.0, DamageType: m_269390, com.cerbon.bosses_of_mass_destruction.item.custom.ChargedEnderPearlEntity#m_5790_#1 -->

### MagicMissileProjectile (Type: Projectile)

- `oneenoughdamage:com/cerbon/bosses_of_mass_destruction/projectile/magic_missile_projectile/entity_hit/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: m_269390, com.cerbon.bosses_of_mass_destruction.projectile.MagicMissileProjectile#entityHit#1 -->

### PetalBladeProjectile (Type: Projectile)

- `oneenoughdamage:com/cerbon/bosses_of_mass_destruction/projectile/petal_blade_projectile/entity_hit/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: m_269390, com.cerbon.bosses_of_mass_destruction.projectile.PetalBladeProjectile#entityHit#1 -->

### SpikeAction (Type: Other)

- `oneenoughdamage:com/cerbon/bosses_of_mass_destruction/entity/custom/obsidilith/spike_action/damage_entity/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: unknown, com.cerbon.bosses_of_mass_destruction.entity.custom.obsidilith.SpikeAction#damageEntity#1 -->

### Spikes (Type: Other)

- `oneenoughdamage:com/cerbon/bosses_of_mass_destruction/entity/custom/void_blossom/spikes/damage_entity/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: unknown, com.cerbon.bosses_of_mass_destruction.entity.custom.void_blossom.Spikes#damageEntity#1 -->

### SporeBallProjectile (Type: Projectile)

- `oneenoughdamage:com/cerbon/bosses_of_mass_destruction/projectile/spore_ball_projectile/entity_hit/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: m_269390, com.cerbon.bosses_of_mass_destruction.projectile.SporeBallProjectile#entityHit#1 -->
- `oneenoughdamage:com/cerbon/bosses_of_mass_destruction/projectile/spore_ball_projectile/lambda_do_explosion_2/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: unknown, com.cerbon.bosses_of_mass_destruction.projectile.SporeBallProjectile#lambda$doExplosion$2#1 -->

### VoidBlossomCompoundHitbox (Type: Other)

- `oneenoughdamage:com/cerbon/bosses_of_mass_destruction/entity/custom/void_blossom/hitbox/void_blossom_compound_hitbox/after_damage/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: m_269374, com.cerbon.bosses_of_mass_destruction.entity.custom.void_blossom.hitbox.VoidBlossomCompoundHitbox#afterDamage#1 -->

### VoidBlossomSpikeTick (Type: Other)

- `oneenoughdamage:com/cerbon/bosses_of_mass_destruction/entity/custom/void_blossom/void_blossom_spike_tick/tick/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: m_269374, com.cerbon.bosses_of_mass_destruction.entity.custom.void_blossom.VoidBlossomSpikeTick#tick#1 -->

### WaveAction (Type: Other)

- `oneenoughdamage:com/cerbon/bosses_of_mass_destruction/entity/custom/obsidilith/wave_action/damage_entity/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: unknown, com.cerbon.bosses_of_mass_destruction.entity.custom.obsidilith.WaveAction#damageEntity#1 -->

## Botania

### BabylonWeaponEntity (Type: Projectile)

- `oneenoughdamage:vazkii/botania/common/entity/babylon_weapon_entity/m_8119/1/r` <!-- mode: replace (/r), default: 20.0, DamageType: m_269075, vazkii.botania.common.entity.BabylonWeaponEntity#m_8119_#1 -->

### BellethornBlockEntity (Type: Other)

- `oneenoughdamage:vazkii/botania/common/block/flower/functional/bellethorn_block_entity/tick_flower/1/r` <!-- mode: replace (/r), default: 20.0, DamageType: m_269425, vazkii.botania.common.block.flower.functional.BellethornBlockEntity#tickFlower#1 -->

### BottledManaItem (Type: Item)

- `oneenoughdamage:vazkii/botania/common/item/bottled_mana_item/effect_drop_own_head/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: m_269425, vazkii.botania.common.item.BottledManaItem#effectDropOwnHead#1 -->

### CloakOfBalanceItem (Type: Item)

- `oneenoughdamage:vazkii/botania/common/item/equipment/bauble/cloak_of_balance_item/effect_on_damage/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: m_269104, vazkii.botania.common.item.equipment.bauble.CloakOfBalanceItem#effectOnDamage#1 -->

### CloakOfSinItem (Type: Item)

- `oneenoughdamage:vazkii/botania/common/item/equipment/bauble/cloak_of_sin_item/effect_on_damage/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: m_269075, vazkii.botania.common.item.equipment.bauble.CloakOfSinItem#effectOnDamage#1 -->

### DamagingLens (Type: Other)

- `oneenoughdamage:vazkii/botania/common/item/lens/damaging_lens/update_burst/1/r` <!-- mode: replace (/r), default: 8.0, DamageType: m_269425, vazkii.botania.common.item.lens.DamagingLens#updateBurst#1 -->

### EnderAirBottleEntity (Type: Projectile)

- `oneenoughdamage:vazkii/botania/common/entity/ender_air_bottle_entity/m_5790/1/r` <!-- mode: replace (/r), default: 0.0, DamageType: m_269390, vazkii.botania.common.entity.EnderAirBottleEntity#m_5790_#1 -->

### FallingStarEntity (Type: Projectile)

- `oneenoughdamage:vazkii/botania/common/entity/falling_star_entity/m_5790/1/r` <!-- mode: replace (/r), default: 5.0, DamageType: unknown, vazkii.botania.common.entity.FallingStarEntity#m_5790_#1 -->
- `oneenoughdamage:vazkii/botania/common/entity/falling_star_entity/m_5790/2/r` <!-- mode: replace (/r), default: 5.0, DamageType: unknown, vazkii.botania.common.entity.FallingStarEntity#m_5790_#2 -->

### MagicLandmineEntity (Type: Entity)

- `oneenoughdamage:vazkii/botania/common/entity/magic_landmine_entity/m_8119/1/r` <!-- mode: replace (/r), default: 10.0, DamageType: m_269104, vazkii.botania.common.entity.MagicLandmineEntity#m_8119_#1 -->

### RelicImpl (Type: Other)

- `oneenoughdamage:vazkii/botania/common/item/relic/relic_impl/tick_binding/1/r` <!-- mode: replace (/r), default: 2.0, DamageType: relicimpl:damage_source, vazkii.botania.common.item.relic.RelicImpl#tickBinding#1 -->

### SoulscribeItem (Type: Item)

- `oneenoughdamage:vazkii/botania/common/item/equipment/tool/soulscribe_item/m_7579/1/r` <!-- mode: replace (/r), default: 20.0, DamageType: m_269075, vazkii.botania.common.item.equipment.tool.SoulscribeItem#m_7579_#1 -->

### TerraBladeItem (Type: Item)

- `oneenoughdamage:vazkii/botania/common/item/equipment/tool/terrasteel/terra_blade_item/update_burst/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: m_269333, vazkii.botania.common.item.equipment.tool.terrasteel.TerraBladeItem#updateBurst#1 -->

### ThornChakramEntity (Type: Projectile)

- `oneenoughdamage:vazkii/botania/common/entity/thorn_chakram_entity/m_5790/1/r` <!-- mode: replace (/r), default: 12.0, DamageType: m_269333, vazkii.botania.common.entity.ThornChakramEntity#m_5790_#1 -->

### ThrownItemEntity (Type: Entity)

- `oneenoughdamage:vazkii/botania/common/entity/thrown_item_entity/m_8119/1/r` <!-- mode: replace (/r), default: 2.0, DamageType: m_269425, vazkii.botania.common.entity.ThrownItemEntity#m_8119_#1 -->

### ThundercallerItem (Type: Item)

- `oneenoughdamage:vazkii/botania/common/item/equipment/tool/thundercaller_item/m_7579/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: m_269075, vazkii.botania.common.item.equipment.tool.ThundercallerItem#m_7579_#1 -->
- `oneenoughdamage:vazkii/botania/common/item/equipment/tool/thundercaller_item/m_7579/2/m` <!-- mode: multiply (/m), default: 1.0, DamageType: m_269333, vazkii.botania.common.item.equipment.tool.ThundercallerItem#m_7579_#2 -->

## Cataclysm

### Abyssal Burn (深渊灼烧) (Type: Effect)

- `oneenoughdamage:com/github/l_ender/cataclysm/effects/effect_abyssal_burn/m_6742/1/r` <!-- mode: replace (/r), default: 1.0, DamageType: m_269079, com.github.L_Ender.cataclysm.effects.EffectAbyssal_Burn#m_6742_#1 -->

### Abyssal Curse (深渊诅咒) (Type: Effect)

- `oneenoughdamage:com/github/l_ender/cataclysm/effects/effect_abyssal_curse/m_6742/1/r` <!-- mode: replace (/r), default: 1.0, DamageType: m_269079, com.github.L_Ender.cataclysm.effects.EffectAbyssal_Curse#m_6742_#1 -->

### Altar of Fire (烈焰祭坛) (Type: Block)

- `oneenoughdamage:com/github/l_ender/cataclysm/blocks/altar_of_fire_block/m_7892/1/r` <!-- mode: replace (/r), default: 3.0, DamageType: m_269387, com.github.L_Ender.cataclysm.blocks.Altar_Of_Fire_Block#m_7892_#1 -->

### Bolt Strike (雷击) (Type: Entity)

- `oneenoughdamage:com/github/l_ender/cataclysm/entity/effect/bolt_strike_entity/damage/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: m_269425, com.github.L_Ender.cataclysm.entity.effect.Bolt_strike_Entity#damage#1 -->
- `oneenoughdamage:com/github/l_ender/cataclysm/entity/effect/bolt_strike_entity/damage/2/m` <!-- mode: multiply (/m), default: 1.0, DamageType: m_269104, com.github.L_Ender.cataclysm.entity.effect.Bolt_strike_Entity#damage#2 -->

### Brontes (Type: Item)

- `oneenoughdamage:com/github/l_ender/cataclysm/entity/projectile/brontes_entity/m_5790/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: cmdamagetypes:cause_player_ceraunus_damage, com.github.L_Ender.cataclysm.entity.projectile.Brontes_Entity#m_5790_#1 -->

### Ceraunus (霆浪锚戟) (Type: Item)

- `oneenoughdamage:com/github/l_ender/cataclysm/entity/projectile/player_ceraunus_entity/m_5790/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: cmdamagetypes:cause_player_ceraunus_damage, com.github.L_Ender.cataclysm.entity.projectile.Player_Ceraunus_Entity#m_5790_#1 -->

### ChargeCapability (Type: Other)

- `oneenoughdamage:com/github/l_ender/cataclysm/capabilities/charge_capability_charge_capability_imp/tick/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: m_269299, com.github.L_Ender.cataclysm.capabilities.ChargeCapability$ChargeCapabilityImp#tick#1 -->

### EMP\_Block\_Entity (Type: Other)

- `oneenoughdamage:com/github/l_ender/cataclysm/blockentities/e_m_p_block_entity/tick/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: cmdamagetypes:get_damage_source, com.github.L_Ender.cataclysm.blockentities.EMP_Block_Entity#tick#1 -->

### IgnisExplosion (Type: Other)

- `oneenoughdamage:com/github/l_ender/cataclysm/util/custom_explosion/ignis_explosion/m_46061/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: unknown, com.github.L_Ender.cataclysm.util.CustomExplosion.IgnisExplosion#m_46061_#1 -->

### Infernal Forge (炼狱锻锤) (Type: Item)

- `oneenoughdamage:com/github/l_ender/cataclysm/items/infernal_forge/earth_quake/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: unknown, com.github.L_Ender.cataclysm.items.Infernal_forge#EarthQuake#1 -->

### Meat Shredder (绞肉锯) (Type: Item)

- `oneenoughdamage:com/github/l_ender/cataclysm/items/meat_shredder/m_5929/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: unknown, com.github.L_Ender.cataclysm.items.Meat_Shredder#m_5929_#1 -->

### Monstrous Helm (恶兽头盔) (Type: Item)

- `oneenoughdamage:com/github/l_ender/cataclysm/items/monstrous_helm/m_6883/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: m_269333, com.github.L_Ender.cataclysm.items.Monstrous_Helm#m_6883_#1 -->

### RenderRushCapability (Type: Other)

- `oneenoughdamage:com/github/l_ender/cataclysm/capabilities/render_rush_capability_render_rush_capability_imp/tick/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: m_269333, com.github.L_Ender.cataclysm.capabilities.RenderRushCapability$RenderRushCapabilityImp#tick#1 -->

### SandstoneIgniteTrap\_Block\_Entity (Type: Other)

- `oneenoughdamage:com/github/l_ender/cataclysm/blockentities/sandstone_ignite_trap_block_entity/tick/1/r` <!-- mode: replace (/r), default: 5.0, DamageType: m_269387, com.github.L_Ender.cataclysm.blockentities.SandstoneIgniteTrap_Block_Entity#tick#1 -->

### The Annihilator (歼灭战锤) (Type: Item)

- `oneenoughdamage:com/github/l_ender/cataclysm/items/the_annihilator/yall/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: m_269333, com.github.L_Ender.cataclysm.items.The_Annihilator#yall#1 -->

### The Immolator (献祭者) (Type: Item)

- `oneenoughdamage:com/github/l_ender/cataclysm/items/the_immolator/yall/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: m_269333, com.github.L_Ender.cataclysm.items.The_Immolator#yall#1 -->

### The Leviathan Tongue (Type: Entity)

- `oneenoughdamage:com/github/l_ender/cataclysm/entity/animation_monster/boss_monsters/the_leviathan/the_leviathan_tongue_entity/hurt_entity/1/r` <!-- mode: replace (/r), default: 6.0, DamageType: m_269333, com.github.L_Ender.cataclysm.entity.AnimationMonster.BossMonsters.The_Leviathan.The_Leviathan_Tongue_Entity#hurtEntity#1 -->

### Tidal Tentacle (潮汐触手) (Type: Entity)

- `oneenoughdamage:com/github/l_ender/cataclysm/entity/projectile/tidal_tentacle_entity/m_8119/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: m_269299, com.github.L_Ender.cataclysm.entity.projectile.Tidal_Tentacle_Entity#m_8119_#1 -->

### Void Howitzer (虚空榴弹) (Type: Projectile)

- `oneenoughdamage:com/github/l_ender/cataclysm/entity/projectile/void_howitzer_entity/m_5790/1/r` <!-- mode: replace (/r), default: 8.0, DamageType: m_269104, com.github.L_Ender.cataclysm.entity.projectile.Void_Howitzer_Entity#m_5790_#1 -->
- `oneenoughdamage:com/github/l_ender/cataclysm/entity/projectile/void_howitzer_entity/m_5790/2/r` <!-- mode: replace (/r), default: 5.0, DamageType: m_269425, com.github.L_Ender.cataclysm.entity.projectile.Void_Howitzer_Entity#m_5790_#2 -->

### Wall Watcher (Type: Entity)

- `oneenoughdamage:com/github/l_ender/cataclysm/entity/effect/wall_watcher_entity/m_8119/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: m_269299, com.github.L_Ender.cataclysm.entity.effect.Wall_Watcher_Entity#m_8119_#1 -->

### Wetness (潮湿) (Type: Effect)

- `oneenoughdamage:com/github/l_ender/cataclysm/effects/effect_wetness/m_6742/1/r` <!-- mode: replace (/r), default: 1.0, DamageType: m_269425, com.github.L_Ender.cataclysm.effects.EffectWetness#m_6742_#1 -->

### Wrath of the Desert (沙暴之怒) (Type: Item)

- `oneenoughdamage:com/github/l_ender/cataclysm/entity/projectile/cursed_sandstorm_entity/m_5790/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: cmdamagetypes:cause_maledictio_sagitta_damage, com.github.L_Ender.cataclysm.entity.projectile.Cursed_Sandstorm_Entity#m_5790_#1 -->
- `oneenoughdamage:com/github/l_ender/cataclysm/entity/projectile/cursed_sandstorm_entity/m_5790/2/m` <!-- mode: multiply (/m), default: 1.0, DamageType: m_269425, com.github.L_Ender.cataclysm.entity.projectile.Cursed_Sandstorm_Entity#m_5790_#2 -->

## Citadel

### PathingStuckHandler (Type: Other)

- `oneenoughdamage:com/github/alexthe666/citadel/server/entity/pathfinding/raycoms/pathing_stuck_handler/complete_stuck_action/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: m_269318, com.github.alexthe666.citadel.server.entity.pathfinding.raycoms.PathingStuckHandler#completeStuckAction#1 -->

## Create

### AllFanProcessingTypes (Type: Other)

- `oneenoughdamage:com/simibubi/create/content/kinetics/fan/processing/all_fan_processing_types_blasting_type/affect_entity/1/r` <!-- mode: replace (/r), default: 4.0, DamageType: unknown, com.simibubi.create.content.kinetics.fan.processing.AllFanProcessingTypes$BlastingType#affectEntity#1 -->
- `oneenoughdamage:com/simibubi/create/content/kinetics/fan/processing/all_fan_processing_types_smoking_type/affect_entity/1/r` <!-- mode: replace (/r), default: 2.0, DamageType: unknown, com.simibubi.create.content.kinetics.fan.processing.AllFanProcessingTypes$SmokingType#affectEntity#1 -->
- `oneenoughdamage:com/simibubi/create/content/kinetics/fan/processing/all_fan_processing_types_splashing_type/affect_entity/1/r` <!-- mode: replace (/r), default: 2.0, DamageType: m_269063, com.simibubi.create.content.kinetics.fan.processing.AllFanProcessingTypes$SplashingType#affectEntity#1 -->

### BlockBreakingMovementBehaviour (Type: Other)

- `oneenoughdamage:com/simibubi/create/content/kinetics/base/block_breaking_movement_behaviour/damage_entities/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: unknown, com.simibubi.create.content.kinetics.base.BlockBreakingMovementBehaviour#damageEntities#1 -->

### ContraptionCollider (Type: Other)

- `oneenoughdamage:com/simibubi/create/content/contraptions/contraption_collider/handle_damage_from_train/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: unknown, com.simibubi.create.content.contraptions.ContraptionCollider#handleDamageFromTrain#1 -->

### CrushingWheelControllerBlockEntity (Type: Other)

- `oneenoughdamage:com/simibubi/create/content/kinetics/crusher/crushing_wheel_controller_block_entity/tick/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: unknown, com.simibubi.create.content.kinetics.crusher.CrushingWheelControllerBlockEntity#tick#1 -->

### DrillBlock (Type: Block)

- `oneenoughdamage:com/simibubi/create/content/kinetics/drill/drill_block/lambda_entity_inside_0/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: unknown, com.simibubi.create.content.kinetics.drill.DrillBlock#lambda$entityInside$0#1 -->

### PotatoProjectileEntity (Type: Projectile)

- `oneenoughdamage:com/simibubi/create/content/equipment/potato_cannon/potato_projectile_entity/m_5790/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: potatoprojectileentity:cause_potato_damage, com.simibubi.create.content.equipment.potatoCannon.PotatoProjectileEntity#m_5790_#1 -->

### SawBlock (Type: Block)

- `oneenoughdamage:com/simibubi/create/content/kinetics/saw/saw_block/lambda_entity_inside_1/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: unknown, com.simibubi.create.content.kinetics.saw.SawBlock#lambda$entityInside$1#1 -->

### WrenchItem (Type: Item)

- `oneenoughdamage:com/simibubi/create/content/equipment/wrench/wrench_item/wrench_insta_kills_minecarts/1/r` <!-- mode: replace (/r), default: 100.0, DamageType: m_269075, com.simibubi.create.content.equipment.wrench.WrenchItem#wrenchInstaKillsMinecarts#1 -->

## Createdieselgenerators

### BurnerBlock (Type: Block)

- `oneenoughdamage:com/jesz/createdieselgenerators/content/burner/burner_block/m_7892/1/r` <!-- mode: replace (/r), default: 1.0, DamageType: m_269387, com.jesz.createdieselgenerators.content.burner.BurnerBlock#m_7892_#1 -->

### ChemicalSprayerProjectileEntity (Type: Projectile)

- `oneenoughdamage:com/jesz/createdieselgenerators/content/tools/chemical_sprayer_projectile_entity/m_5790/1/r` <!-- mode: replace (/r), default: 2.0, DamageType: m_269387, com.jesz.createdieselgenerators.content.tools.ChemicalSprayerProjectileEntity#m_5790_#1 -->
- `oneenoughdamage:com/jesz/createdieselgenerators/content/tools/chemical_sprayer_projectile_entity/m_5790/2/r` <!-- mode: replace (/r), default: 0.5, DamageType: m_269264, com.jesz.createdieselgenerators.content.tools.ChemicalSprayerProjectileEntity#m_5790_#2 -->
- `oneenoughdamage:com/jesz/createdieselgenerators/content/tools/chemical_sprayer_projectile_entity/m_5790/3/r` <!-- mode: replace (/r), default: 0.5, DamageType: m_269264, com.jesz.createdieselgenerators.content.tools.ChemicalSprayerProjectileEntity#m_5790_#3 -->

## Curios

### SummoningFocus (Type: Item)

- `oneenoughdamage:com/hollingsworth/arsnouveau/common/items/curios/summoning_focus/summon_death_event/1/r` <!-- mode: replace (/r), default: 5.0, DamageType: m_269374, com.hollingsworth.arsnouveau.common.items.curios.SummoningFocus#summonDeathEvent#1 -->

## Deeperdarker

### SculkJawBlock (Type: Block)

- `oneenoughdamage:com/kyanite/deeperdarker/content/blocks/sculk_jaw_block/m_141947/1/r` <!-- mode: replace (/r), default: 3.0, DamageType: unknown, com.kyanite.deeperdarker.content.blocks.SculkJawBlock#m_141947_#1 -->
- `oneenoughdamage:com/kyanite/deeperdarker/content/blocks/sculk_jaw_block/m_7892/1/r` <!-- mode: replace (/r), default: 3.0, DamageType: unknown, com.kyanite.deeperdarker.content.blocks.SculkJawBlock#m_7892_#1 -->

### SonorousStaffItem (Type: Item)

- `oneenoughdamage:com/kyanite/deeperdarker/content/items/sonorous_staff_item/m_5551/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: m_269285, com.kyanite.deeperdarker.content.items.SonorousStaffItem#m_5551_#1 -->

## Extrabotany

### AchillesShieldItem (Type: Item)

- `oneenoughdamage:io/github/lounode/extrabotany/common/item/relic/achilles_shield_item/on_shield_block/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: m_269374, io.github.lounode.extrabotany.common.item.relic.AchillesShieldItem#onShieldBlock#1 -->

### AuraFireEntity (Type: Projectile)

- `oneenoughdamage:io/github/lounode/extrabotany/common/entity/aura_fire_entity/m_8119/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: aurafireentity:create_damage_source, io.github.lounode.extrabotany.common.entity.AuraFireEntity#m_8119_#1 -->

### BloodEnchantressBlockEntity (Type: Other)

- `oneenoughdamage:io/github/lounode/extrabotany/common/block/flower/generating/blood_enchantress_block_entity/tick_flower/1/r` <!-- mode: replace (/r), default: 3.0, DamageType: m_269264, io.github.lounode.extrabotany.common.block.flower.generating.BloodEnchantressBlockEntity#tickFlower#1 -->

### CoreOfTheVoidItem (Type: Item)

- `oneenoughdamage:io/github/lounode/extrabotany/common/item/relic/voidcore/core_of_the_void_item/on_worn_tick/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: coreofthevoiditem:damage_source, io.github.lounode.extrabotany.common.item.relic.voidcore.CoreOfTheVoidItem#onWornTick#1 -->

### ExcaliburItem (Type: Item)

- `oneenoughdamage:io/github/lounode/extrabotany/common/item/relic/excalibur_item/update_burst/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: extrabotanydamagetypes_sources:excalibur_damage, io.github.lounode.extrabotany.common.item.relic.ExcaliburItem#updateBurst#1 -->

### FailnaughtItem (Type: Item)

- `oneenoughdamage:io/github/lounode/extrabotany/common/item/relic/failnaught_item/update_burst/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: m_269075, io.github.lounode.extrabotany.common.item.relic.FailnaughtItem#updateBurst#1 -->

### HealReverseMobEffect (Type: Effect)

- `oneenoughdamage:io/github/lounode/extrabotany/common/brew/effect/heal_reverse_mob_effect/on_living_heal/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: extrabotanydamagetypes_sources:reverse_heal_damage, io.github.lounode.extrabotany.common.brew.effect.HealReverseMobEffect#onLivingHeal#1 -->

### LinkMobEffect (Type: Effect)

- `oneenoughdamage:io/github/lounode/extrabotany/common/brew/effect/link_mob_effect/lambda_on_entity_damaged_2/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: linkmobeffect:damage_source, io.github.lounode.extrabotany.common.brew.effect.LinkMobEffect#lambda$onEntityDamaged$2#1 -->

### MagicLandMineEntity (Type: Entity)

- `oneenoughdamage:io/github/lounode/extrabotany/common/entity/magic_land_mine_entity/explode/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: m_269104, io.github.lounode.extrabotany.common.entity.MagicLandMineEntity#explode#1 -->

### NecrofleurBlockEntity (Type: Other)

- `oneenoughdamage:io/github/lounode/extrabotany/common/block/flower/functional/necrofleur_block_entity/tick_flower/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: m_269104, io.github.lounode.extrabotany.common.block.flower.functional.NecrofleurBlockEntity#tickFlower#1 -->

### SkullMissileEntity (Type: Projectile)

- `oneenoughdamage:io/github/lounode/extrabotany/common/entity/skull_missile_entity/lambda_on_hit_entity_2/1/r` <!-- mode: replace (/r), default: 12.0, DamageType: skullmissileentity:get_damage_source, io.github.lounode.extrabotany.common.entity.SkullMissileEntity#lambda$onHitEntity$2#1 -->

### TerrasteelShieldItem (Type: Item)

- `oneenoughdamage:io/github/lounode/extrabotany/common/item/equipment/shield/terrasteel_shield_item/on_shield_block/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: terrasteelshielditem:damage_source, io.github.lounode.extrabotany.common.item.equipment.shield.TerrasteelShieldItem#onShieldBlock#1 -->

### ThirrorMobEffect (Type: Other)

- `oneenoughdamage:io/github/lounode/extrabotany/common/brew/effect/thirror_mob_effect_event_handler/on_living_attack/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: m_269374, io.github.lounode.extrabotany.common.brew.effect.ThirrorMobEffect$EventHandler#onLivingAttack#1 -->

### Tracking (Type: Other)

- `oneenoughdamage:io/github/lounode/extrabotany/common/item/lens/tracking/update_burst/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: extrabotanydamagetypes_sources:excalibur_damage, io.github.lounode.extrabotany.common.item.lens.Tracking#updateBurst#1 -->

## Farmersdelight

### AbstractStoveBlock (Type: Block)

- `oneenoughdamage:vectorwing/farmersdelight/common/block/abstract_stove_block/burn_entity_stepping_on_stove/1/r` <!-- mode: replace (/r), default: 1.0, DamageType: moddamagetypes:get_simple_damage_source, vectorwing.farmersdelight.common.block.AbstractStoveBlock#burnEntitySteppingOnStove#1 -->

### RottenTomatoEntity (Type: Projectile)

- `oneenoughdamage:vectorwing/farmersdelight/common/entity/rotten_tomato_entity/m_5790/1/r` <!-- mode: replace (/r), default: 0.0, DamageType: m_269390, vectorwing.farmersdelight.common.entity.RottenTomatoEntity#m_5790_#1 -->

## Forge

### ForgeBalmCommonEvents (Type: Other)

- `oneenoughdamage:net/blay09/mods/balm/forge/event/forge_balm_common_events/lambda_register_events_30/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: m_268989, net.blay09.mods.balm.forge.event.ForgeBalmCommonEvents#lambda$registerEvents$30#1 -->

## Hollingsworth

### ANExplosion (Type: Other)

- `oneenoughdamage:com/hollingsworth/arsnouveau/api/util/a_n_explosion/m_46061/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: unknown, com.hollingsworth.arsnouveau.api.util.ANExplosion#m_46061_#1 -->

### IceShardEntity (Type: Projectile)

- `oneenoughdamage:com/hollingsworth/arsnouveau/common/entity/ice_shard_entity/call_on_broken_after_fall/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: unknown, com.hollingsworth.arsnouveau.common.entity.IceShardEntity#callOnBrokenAfterFall#1 -->

### IDamageEffect (Type: Other)

- `oneenoughdamage:com/hollingsworth/arsnouveau/api/spell/i_damage_effect/attempt_damage/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: unknown, com.hollingsworth.arsnouveau.api.spell.IDamageEffect#attemptDamage#1 -->

### RitualHealing (Type: Other)

- `oneenoughdamage:com/hollingsworth/arsnouveau/common/ritual/ritual_healing/tick/1/r` <!-- mode: replace (/r), default: 10.0, DamageType: m_269075, com.hollingsworth.arsnouveau.common.ritual.RitualHealing#tick#1 -->

### ShockedEffect (Type: Effect)

- `oneenoughdamage:com/hollingsworth/arsnouveau/common/potions/shocked_effect/m_6742/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: m_269548, com.hollingsworth.arsnouveau.common.potions.ShockedEffect#m_6742_#1 -->

### SourceBerryBush (Type: Block)

- `oneenoughdamage:com/hollingsworth/arsnouveau/common/block/source_berry_bush/m_7892/1/r` <!-- mode: replace (/r), default: 1.0, DamageType: m_269555, com.hollingsworth.arsnouveau.common.block.SourceBerryBush#m_7892_#1 -->

## Iceandfire

### BlockIceSpikes (Type: Block)

- `oneenoughdamage:com/iafenvoy/iceandfire/item/block/block_ice_spikes/m_141947/1/r` <!-- mode: replace (/r), default: 1.0, DamageType: m_269325, com.iafenvoy.iceandfire.item.block.BlockIceSpikes#m_141947_#1 -->

### DragonSteelOverrides (Type: Other)

- `oneenoughdamage:com/iafenvoy/iceandfire/item/tool/dragon_steel_overrides/hurt_enemy/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: m_269425, com.iafenvoy.iceandfire.item.tool.DragonSteelOverrides#hurtEnemy#1 -->
- `oneenoughdamage:com/iafenvoy/iceandfire/item/tool/dragon_steel_overrides/hurt_enemy/2/m` <!-- mode: multiply (/m), default: 1.0, DamageType: m_269333, com.iafenvoy.iceandfire.item.tool.DragonSteelOverrides#hurtEnemy#2 -->

### EntityCockatriceEgg (Type: Projectile)

- `oneenoughdamage:com/iafenvoy/iceandfire/entity/entity_cockatrice_egg/m_6532/1/r` <!-- mode: replace (/r), default: 0.0, DamageType: m_269390, com.iafenvoy.iceandfire.entity.EntityCockatriceEgg#m_6532_#1 -->

### EntityDeathWormEgg (Type: Projectile)

- `oneenoughdamage:com/iafenvoy/iceandfire/entity/entity_death_worm_egg/m_6532/1/r` <!-- mode: replace (/r), default: 0.0, DamageType: m_269390, com.iafenvoy.iceandfire.entity.EntityDeathWormEgg#m_6532_#1 -->

### EntityDragonCharge (Type: Projectile)

- `oneenoughdamage:com/iafenvoy/iceandfire/entity/entity_dragon_charge/m_6532/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: entitydragoncharge:cause_damage, com.iafenvoy.iceandfire.entity.EntityDragonCharge#m_6532_#1 -->

### EntityGhostSword (Type: Projectile)

- `oneenoughdamage:com/iafenvoy/iceandfire/entity/entity_ghost_sword/m_5790/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: unknown, com.iafenvoy.iceandfire.entity.EntityGhostSword#m_5790_#1 -->

### EntityHippogryphEgg (Type: Projectile)

- `oneenoughdamage:com/iafenvoy/iceandfire/entity/entity_hippogryph_egg/m_6532/1/r` <!-- mode: replace (/r), default: 0.0, DamageType: m_269390, com.iafenvoy.iceandfire.entity.EntityHippogryphEgg#m_6532_#1 -->

### EntityMultipartPart (Type: Entity)

- `oneenoughdamage:com/iafenvoy/iceandfire/entity/entity_multipart_part/m_6469/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: unknown, com.iafenvoy.iceandfire.entity.EntityMultipartPart#m_6469_#1 -->

### EntityPixieCharge (Type: Projectile)

- `oneenoughdamage:com/iafenvoy/iceandfire/entity/entity_pixie_charge/m_6532/1/r` <!-- mode: replace (/r), default: 5.0, DamageType: m_269104, com.iafenvoy.iceandfire.entity.EntityPixieCharge#m_6532_#1 -->

### EntityTideTrident (Type: Projectile)

- `oneenoughdamage:com/iafenvoy/iceandfire/entity/entity_tide_trident/m_5790/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: unknown, com.iafenvoy.iceandfire.entity.EntityTideTrident#m_5790_#1 -->

### IafDragonDestructionManager (Type: Other)

- `oneenoughdamage:com/iafenvoy/iceandfire/entity/util/dragon/iaf_dragon_destruction_manager/lambda_destroy_area_breath_2/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: unknown, com.iafenvoy.iceandfire.entity.util.dragon.IafDragonDestructionManager#lambda$destroyAreaBreath$2#1 -->
- `oneenoughdamage:com/iafenvoy/iceandfire/entity/util/dragon/iaf_dragon_destruction_manager/lambda_destroy_area_charge_5/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: unknown, com.iafenvoy.iceandfire.entity.util.dragon.IafDragonDestructionManager#lambda$destroyAreaCharge$5#1 -->

### IafDragonLogic (Type: Other)

- `oneenoughdamage:com/iafenvoy/iceandfire/entity/util/dragon/iaf_dragon_logic/attack_target/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: m_269333, com.iafenvoy.iceandfire.entity.util.dragon.IafDragonLogic#attackTarget#1 -->
- `oneenoughdamage:com/iafenvoy/iceandfire/entity/util/dragon/iaf_dragon_logic/attack_target/2/m` <!-- mode: multiply (/m), default: 1.0, DamageType: m_269104, com.iafenvoy.iceandfire.entity.util.dragon.IafDragonLogic#attackTarget#2 -->

### ItemAlchemySword (Type: Item)

- `oneenoughdamage:com/iafenvoy/iceandfire/item/tool/item_alchemy_sword/m_7579/1/r` <!-- mode: replace (/r), default: 13.5, DamageType: m_269387, com.iafenvoy.iceandfire.item.tool.ItemAlchemySword#m_7579_#1 -->
- `oneenoughdamage:com/iafenvoy/iceandfire/item/tool/item_alchemy_sword/m_7579/2/r` <!-- mode: replace (/r), default: 13.5, DamageType: m_269063, com.iafenvoy.iceandfire.item.tool.ItemAlchemySword#m_7579_#2 -->
- `oneenoughdamage:com/iafenvoy/iceandfire/item/tool/item_alchemy_sword/m_7579/3/r` <!-- mode: replace (/r), default: 9.5, DamageType: m_269548, com.iafenvoy.iceandfire.item.tool.ItemAlchemySword#m_7579_#3 -->

### ItemCockatriceScepter (Type: Item)

- `oneenoughdamage:com/iafenvoy/iceandfire/item/item_cockatrice_scepter/attack_targets/1/r` <!-- mode: replace (/r), default: 2.0, DamageType: m_269251, com.iafenvoy.iceandfire.item.ItemCockatriceScepter#attackTargets#1 -->

### ItemDeathwormGauntlet (Type: Item)

- `oneenoughdamage:com/iafenvoy/iceandfire/item/item_deathworm_gauntlet/m_5922/1/r` <!-- mode: replace (/r), default: 3.0, DamageType: m_269075, com.iafenvoy.iceandfire.item.ItemDeathwormGauntlet#m_5922_#1 -->

### ItemGorgonHead (Type: Item)

- `oneenoughdamage:com/iafenvoy/iceandfire/item/item_gorgon_head/m_5551/1/r` <!-- mode: replace (/r), default: 2.14748365E9, DamageType: unknown, com.iafenvoy.iceandfire.item.ItemGorgonHead#m_5551_#1 -->

### ItemHippogryphSword (Type: Item)

- `oneenoughdamage:com/iafenvoy/iceandfire/item/tool/item_hippogryph_sword/m_7579/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: m_269075, com.iafenvoy.iceandfire.item.tool.ItemHippogryphSword#m_7579_#1 -->

### ServerNetworkHelper (Type: Other)

- `oneenoughdamage:com/iafenvoy/iceandfire/network/server_network_helper/lambda_register_receivers_1/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: m_269333, com.iafenvoy.iceandfire.network.ServerNetworkHelper#lambda$registerReceivers$1#1 -->

## Irons Spellbooks

### Dragon Breath (龙息) (Type: Projectile)

- `oneenoughdamage:io/redspace/ironsspellbooks/entity/spells/dragon_breath/dragon_breath_pool/apply_effect/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: dragonbreathpool:damage_source, io.redspace.ironsspellbooks.entity.spells.dragon_breath.DragonBreathPool#applyEffect#1 -->

### Earthquake (地震) (Type: Projectile)

- `oneenoughdamage:io/redspace/ironsspellbooks/entity/spells/earthquake_aoe/apply_effect/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: unknown, io.redspace.ironsspellbooks.entity.spells.EarthquakeAoe#applyEffect#1 -->

### Fiery Field (灼焰场域) (Type: Projectile)

- `oneenoughdamage:io/redspace/ironsspellbooks/entity/spells/magma_ball/fire_field/apply_effect/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: firefield:damage_source, io.redspace.ironsspellbooks.entity.spells.magma_ball.FireField#applyEffect#1 -->

### Poison Cloud (毒云) (Type: Projectile)

- `oneenoughdamage:io/redspace/ironsspellbooks/entity/spells/poison_cloud/poison_cloud/apply_effect/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: poisoncloud:damage_source, io.redspace.ironsspellbooks.entity.spells.poison_cloud.PoisonCloud#applyEffect#1 -->

### Staff of the Nines (九神魔杖) (Type: Item)

- `oneenoughdamage:io/redspace/ironsspellbooks/item/weapons/staff_of_the_nines/m_7203/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: m_269425, io.redspace.ironsspellbooks.item.weapons.StaffOfTheNines#m_7203_#1 -->

## Jerry

### NaquadahReactorMultiblockData (Type: Other)

- `oneenoughdamage:com/jerry/generator_extras/common/content/naquadah/naquadah_reactor_multiblock_data/kill/1/r` <!-- mode: replace (/r), default: 50000.0, DamageType: m_269425, com.jerry.generator_extras.common.content.naquadah.NaquadahReactorMultiblockData#kill#1 -->

## Kubejs

### EntityKJS (Type: Other)

- `oneenoughdamage:dev/latvian/mods/kubejs/core/entity_k_j_s/kjs_attack/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: m_269264, dev.latvian.mods.kubejs.core.EntityKJS#kjs$attack#1 -->

## Mekanism

### DefaultRadiationEntity (Type: Other)

- `oneenoughdamage:mekanism/common/lib/radiation/capability/default_radiation_entity/update/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: unknown, mekanism.common.lib.radiation.capability.DefaultRadiationEntity#update#1 -->
- `oneenoughdamage:mekanism/common/lib/radiation/capability/default_radiation_entity/update/2/m` <!-- mode: multiply (/m), default: 1.0, DamageType: unknown, mekanism.common.lib.radiation.capability.DefaultRadiationEntity#update#2 -->

### EntityFlame (Type: Projectile)

- `oneenoughdamage:mekanism/common/entity/entity_flame/burn/1/r` <!-- mode: replace (/r), default: 10.0, DamageType: m_269390, mekanism.common.entity.EntityFlame#burn#1 -->

### FusionReactorMultiblockData (Type: Other)

- `oneenoughdamage:mekanism/generators/common/content/fusion/fusion_reactor_multiblock_data/kill/1/r` <!-- mode: replace (/r), default: 50000.0, DamageType: m_269425, mekanism.generators.common.content.fusion.FusionReactorMultiblockData#kill#1 -->

### SPSMultiblockData (Type: Other)

- `oneenoughdamage:mekanism/common/content/sps/s_p_s_multiblock_data/kill/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: m_269425, mekanism.common.content.sps.SPSMultiblockData#kill#1 -->

### TileEntityBasicLaser (Type: Other)

- `oneenoughdamage:mekanism/common/tile/laser/tile_entity_basic_laser/on_update_server/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: unknown, mekanism.common.tile.laser.TileEntityBasicLaser#onUpdateServer#1 -->

## Meowmel

### DamageEventDispatcher (Type: Other)

- `oneenoughdamage:meowmel/damage/damage_event_dispatcher/aoe_damage/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: unknown, meowmel.damage.DamageEventDispatcher#aoeDamage#1 -->
- `oneenoughdamage:meowmel/damage/damage_event_dispatcher/handle_burn/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: unknown, meowmel.damage.DamageEventDispatcher#handleBurn#1 -->
- `oneenoughdamage:meowmel/damage/damage_event_dispatcher/handle_electro_charged/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: unknown, meowmel.damage.DamageEventDispatcher#handleElectroCharged#1 -->
- `oneenoughdamage:meowmel/damage/damage_event_dispatcher/handle_electro_charged/2/m` <!-- mode: multiply (/m), default: 1.0, DamageType: unknown, meowmel.damage.DamageEventDispatcher#handleElectroCharged#2 -->
- `oneenoughdamage:meowmel/damage/damage_event_dispatcher/handle_overload/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: unknown, meowmel.damage.DamageEventDispatcher#handleOverload#1 -->
- `oneenoughdamage:meowmel/damage/damage_event_dispatcher/handle_superconduct/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: unknown, meowmel.damage.DamageEventDispatcher#handleSuperconduct#1 -->
- `oneenoughdamage:meowmel/damage/damage_event_dispatcher/handle_swirl/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: unknown, meowmel.damage.DamageEventDispatcher#handleSwirl#1 -->

### DendroCoreEntity (Type: Entity)

- `oneenoughdamage:meowmel/entity/dendro_core_entity/explode/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: m_269093, meowmel.entity.DendroCoreEntity#explode#1 -->

## Minecraft

### BaseFireBlock (Type: Block)

- `oneenoughdamage:net/minecraft/world/level/block/base_fire_block/m_7892/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: m_269387, net.minecraft.world.level.block.BaseFireBlock#m_7892_#1 -->

### CactusBlock (Type: Block)

- `oneenoughdamage:net/minecraft/world/level/block/cactus_block/m_7892/1/r` <!-- mode: replace (/r), default: 1.0, DamageType: m_269325, net.minecraft.world.level.block.CactusBlock#m_7892_#1 -->

### CampfireBlock (Type: Block)

- `oneenoughdamage:net/minecraft/world/level/block/campfire_block/m_7892/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: m_269387, net.minecraft.world.level.block.CampfireBlock#m_7892_#1 -->

### ConduitBlockEntity (Type: Other)

- `oneenoughdamage:net/minecraft/world/level/block/entity/conduit_block_entity/m_155408/1/r` <!-- mode: replace (/r), default: 4.0, DamageType: m_269425, net.minecraft.world.level.block.entity.ConduitBlockEntity#m_155408_#1 -->

### DamageCommand (Type: Other)

- `oneenoughdamage:net/minecraft/server/commands/damage_command/m_269485/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: unknown, net.minecraft.server.commands.DamageCommand#m_269485_#1 -->

### Entity (Type: Entity)

- `oneenoughdamage:net/minecraft/world/entity/entity/m_20093/1/r` <!-- mode: replace (/r), default: 4.0, DamageType: m_269233, net.minecraft.world.entity.Entity#m_20093_#1 -->
- `oneenoughdamage:net/minecraft/world/entity/entity/m_6075/1/r` <!-- mode: replace (/r), default: 1.0, DamageType: m_269549, net.minecraft.world.entity.Entity#m_6075_#1 -->
- `oneenoughdamage:net/minecraft/world/entity/entity/m_8038/1/r` <!-- mode: replace (/r), default: 5.0, DamageType: m_269548, net.minecraft.world.entity.Entity#m_8038_#1 -->

### Explosion (Type: Other)

- `oneenoughdamage:net/minecraft/world/level/explosion/m_46061/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: unknown, net.minecraft.world.level.Explosion#m_46061_#1 -->

### FoodData (Type: Other)

- `oneenoughdamage:net/minecraft/world/food/food_data/m_38710/1/r` <!-- mode: replace (/r), default: 1.0, DamageType: m_269064, net.minecraft.world.food.FoodData#m_38710_#1 -->

### HangingEntity (Type: Entity)

- `oneenoughdamage:net/minecraft/world/entity/decoration/hanging_entity/m_7313/1/r` <!-- mode: replace (/r), default: 0.0, DamageType: m_269075, net.minecraft.world.entity.decoration.HangingEntity#m_7313_#1 -->

### HoglinBase (Type: Other)

- `oneenoughdamage:net/minecraft/world/entity/monster/hoglin/hoglin_base/m_34642/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: m_269333, net.minecraft.world.entity.monster.hoglin.HoglinBase#m_34642_#1 -->

### Magma Block (Type: Block)

- `oneenoughdamage:net/minecraft/world/level/block/magma_block/m_141947/1/r` <!-- mode: replace (/r), default: 1.0, DamageType: m_269047, net.minecraft.world.level.block.MagmaBlock#m_141947_#1 -->

### MobEffect (Type: Effect)

- `oneenoughdamage:net/minecraft/world/effect/mob_effect/m_19461/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: m_269425, net.minecraft.world.effect.MobEffect#m_19461_#1 -->
- `oneenoughdamage:net/minecraft/world/effect/mob_effect/m_19461/2/m` <!-- mode: multiply (/m), default: 1.0, DamageType: m_269104, net.minecraft.world.effect.MobEffect#m_19461_#2 -->
- `oneenoughdamage:net/minecraft/world/effect/mob_effect/m_6742/1/r` <!-- mode: replace (/r), default: 1.0, DamageType: m_269425, net.minecraft.world.effect.MobEffect#m_6742_#1 -->
- `oneenoughdamage:net/minecraft/world/effect/mob_effect/m_6742/2/r` <!-- mode: replace (/r), default: 1.0, DamageType: m_269251, net.minecraft.world.effect.MobEffect#m_6742_#2 -->
- `oneenoughdamage:net/minecraft/world/effect/mob_effect/m_6742/3/m` <!-- mode: multiply (/m), default: 1.0, DamageType: m_269425, net.minecraft.world.effect.MobEffect#m_6742_#3 -->

### SweetBerryBushBlock (Type: Block)

- `oneenoughdamage:net/minecraft/world/level/block/sweet_berry_bush_block/m_7892/1/r` <!-- mode: replace (/r), default: 1.0, DamageType: m_269555, net.minecraft.world.level.block.SweetBerryBushBlock#m_7892_#1 -->

### ThornsEnchantment (Type: Other)

- `oneenoughdamage:net/minecraft/world/item/enchantment/thorns_enchantment/m_7675/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: m_269374, net.minecraft.world.item.enchantment.ThornsEnchantment#m_7675_#1 -->

### ThrownEgg (Type: Projectile)

- `oneenoughdamage:net/minecraft/world/entity/projectile/thrown_egg/m_5790/1/r` <!-- mode: replace (/r), default: 0.0, DamageType: m_269390, net.minecraft.world.entity.projectile.ThrownEgg#m_5790_#1 -->

### ThrownEnderpearl (Type: Projectile)

- `oneenoughdamage:net/minecraft/world/entity/projectile/thrown_enderpearl/m_5790/1/r` <!-- mode: replace (/r), default: 0.0, DamageType: m_269390, net.minecraft.world.entity.projectile.ThrownEnderpearl#m_5790_#1 -->
- `oneenoughdamage:net/minecraft/world/entity/projectile/thrown_enderpearl/m_6532/1/r` <!-- mode: replace (/r), default: 5.0, DamageType: m_268989, net.minecraft.world.entity.projectile.ThrownEnderpearl#m_6532_#1 -->

## Minecraftforge

### ForgeHooks (Type: Other)

- `oneenoughdamage:net/minecraftforge/common/forge_hooks/on_living_breathe/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: m_269063, net.minecraftforge.common.ForgeHooks#onLivingBreathe#1 -->

## Obscuria

### ObscureAPIAttributes (Type: Other)

- `oneenoughdamage:com/obscuria/obscureapi/registry/obscure_a_p_i_attributes/parry_and_dodge_event/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: m_269333, com.obscuria.obscureapi.registry.ObscureAPIAttributes#parryAndDodgeEvent#1 -->

## Organeffects

### OrganEffectsExtensionApi (Type: Other)

- `oneenoughdamage:cn/kuzuanpa/organeffects/api/extension/organ_effects_extension_api_damage_nearby_entities_executor/execute/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: m_269075, cn.kuzuanpa.organeffects.api.extension.OrganEffectsExtensionApi$DamageNearbyEntitiesExecutor#execute#1 -->
- `oneenoughdamage:cn/kuzuanpa/organeffects/api/extension/organ_effects_extension_api_damage_self_executor/execute/1/r` <!-- mode: replace (/r), default: 1.0, DamageType: m_269264, cn.kuzuanpa.organeffects.api.extension.OrganEffectsExtensionApi$DamageSelfExecutor#execute#1 -->
- `oneenoughdamage:cn/kuzuanpa/organeffects/api/extension/organ_effects_extension_api_damage_target_executor/execute/1/r` <!-- mode: replace (/r), default: 1.0, DamageType: m_269264, cn.kuzuanpa.organeffects.api.extension.OrganEffectsExtensionApi$DamageTargetExecutor#execute#1 -->

### SkillManager (Type: Other)

- `oneenoughdamage:cn/kuzuanpa/organeffects/common/skill/skill_manager/tick_guardian_beam/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: m_269104, cn.kuzuanpa.organeffects.common.skill.SkillManager#tickGuardianBeam#1 -->

## Organsynergia

### SynergiaAttackBridge (Type: Other)

- `oneenoughdamage:cn/kuzuanpa/organsynergia/compat/synergia_attack_bridge/aoe_damage/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: unknown, cn.kuzuanpa.organsynergia.compat.SynergiaAttackBridge#aoeDamage#1 -->
- `oneenoughdamage:cn/kuzuanpa/organsynergia/compat/synergia_attack_bridge/handle_burn/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: unknown, cn.kuzuanpa.organsynergia.compat.SynergiaAttackBridge#handleBurn#1 -->
- `oneenoughdamage:cn/kuzuanpa/organsynergia/compat/synergia_attack_bridge/handle_electro_charged/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: unknown, cn.kuzuanpa.organsynergia.compat.SynergiaAttackBridge#handleElectroCharged#1 -->
- `oneenoughdamage:cn/kuzuanpa/organsynergia/compat/synergia_attack_bridge/handle_electro_charged/2/m` <!-- mode: multiply (/m), default: 1.0, DamageType: unknown, cn.kuzuanpa.organsynergia.compat.SynergiaAttackBridge#handleElectroCharged#2 -->
- `oneenoughdamage:cn/kuzuanpa/organsynergia/compat/synergia_attack_bridge/handle_overload/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: unknown, cn.kuzuanpa.organsynergia.compat.SynergiaAttackBridge#handleOverload#1 -->
- `oneenoughdamage:cn/kuzuanpa/organsynergia/compat/synergia_attack_bridge/handle_superconduct/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: unknown, cn.kuzuanpa.organsynergia.compat.SynergiaAttackBridge#handleSuperconduct#1 -->
- `oneenoughdamage:cn/kuzuanpa/organsynergia/compat/synergia_attack_bridge/handle_swirl/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: unknown, cn.kuzuanpa.organsynergia.compat.SynergiaAttackBridge#handleSwirl#1 -->

## Plus

### BlazeStoveBlock (Type: Block)

- `oneenoughdamage:plus/dragons/createcentralkitchen/content/contraptions/blaze_stove/blaze_stove_block/m_141947/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: moddamagetypes:get_simple_damage_source, plus.dragons.createcentralkitchen.content.contraptions.blazeStove.BlazeStoveBlock#m_141947_#1 -->

## Redspace

### AirborneEffect (Type: Effect)

- `oneenoughdamage:io/redspace/ironsspellbooks/effect/airborne_effect/m_6742/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: m_269515, io.redspace.ironsspellbooks.effect.AirborneEffect#m_6742_#1 -->

### AlchemistCauldronBlock (Type: Block)

- `oneenoughdamage:io/redspace/ironsspellbooks/block/alchemist_cauldron/alchemist_cauldron_block/m_7892/1/r` <!-- mode: replace (/r), default: 2.0, DamageType: unknown, io.redspace.ironsspellbooks.block.alchemist_cauldron.AlchemistCauldronBlock#m_7892_#1 -->

### BloodCauldronBlock (Type: Block)

- `oneenoughdamage:io/redspace/ironsspellbooks/block/blood_cauldron_block/attempt_cook_entity/1/r` <!-- mode: replace (/r), default: 2.0, DamageType: unknown, io.redspace.ironsspellbooks.block.BloodCauldronBlock#attemptCookEntity#1 -->

### BrazierBlock (Type: Block)

- `oneenoughdamage:io/redspace/ironsspellbooks/block/brazier_block/m_7892/1/r` <!-- mode: replace (/r), default: 1.0, DamageType: m_269387, io.redspace.ironsspellbooks.block.BrazierBlock#m_7892_#1 -->

### DamageSources (Type: Other)

- `oneenoughdamage:io/redspace/ironsspellbooks/damage/damage_sources/apply_damage/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: unknown, io.redspace.ironsspellbooks.damage.DamageSources#applyDamage#1 -->
- `oneenoughdamage:io/redspace/ironsspellbooks/damage/damage_sources/apply_damage/2/m` <!-- mode: multiply (/m), default: 1.0, DamageType: unknown, io.redspace.ironsspellbooks.damage.DamageSources#applyDamage#2 -->

### DeadKingAnimatedWarlockAttackGoal (Type: Other)

- `oneenoughdamage:io/redspace/ironsspellbooks/entity/mobs/dead_king_boss/goals/dead_king_animated_warlock_attack_goal/lambda_handle_attack_logic_0/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: m_269333, io.redspace.ironsspellbooks.entity.mobs.dead_king_boss.goals.DeadKingAnimatedWarlockAttackGoal#lambda$handleAttackLogic$0#1 -->

### FieryDaggerEntity (Type: Projectile)

- `oneenoughdamage:io/redspace/ironsspellbooks/entity/spells/fiery_dagger/fiery_dagger_entity/m_5790/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: unknown, io.redspace.ironsspellbooks.entity.spells.fiery_dagger.FieryDaggerEntity#m_5790_#1 -->

### HeartstopEffect (Type: Effect)

- `oneenoughdamage:io/redspace/ironsspellbooks/effect/heartstop_effect/on_effect_removed/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: unknown, io.redspace.ironsspellbooks.effect.HeartstopEffect#onEffectRemoved#1 -->

### ImmolateEffect (Type: Effect)

- `oneenoughdamage:io/redspace/ironsspellbooks/effect/immolate_effect/m_6742/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: unknown, io.redspace.ironsspellbooks.effect.ImmolateEffect#m_6742_#1 -->

### OminousFireOrbEntity (Type: Entity)

- `oneenoughdamage:io/redspace/ironsspellbooks/entity/mobs/wizards/fire_boss/fire_orb/ominous_fire_orb_entity/do_explosion/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: unknown, io.redspace.ironsspellbooks.entity.mobs.wizards.fire_boss.fire_orb.OminousFireOrbEntity#doExplosion#1 -->

### PortalEntity (Type: Entity)

- `oneenoughdamage:io/redspace/ironsspellbooks/entity/spells/portal/portal_entity/handle_loop_tracking/1/r` <!-- mode: replace (/r), default: 3.4028235E38, DamageType: m_287172, io.redspace.ironsspellbooks.entity.spells.portal.PortalEntity#handleLoopTracking#1 -->

### ServerPlayerEvents (Type: Other)

- `oneenoughdamage:io/redspace/ironsspellbooks/player/server_player_events/use_on_entity_event/1/r` <!-- mode: replace (/r), default: 5.0, DamageType: m_269264, io.redspace.ironsspellbooks.player.ServerPlayerEvents#useOnEntityEvent#1 -->

### ThrownSpear (Type: Projectile)

- `oneenoughdamage:io/redspace/ironsspellbooks/entity/spells/thrown_spear/thrown_spear/m_5790/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: unknown, io.redspace.ironsspellbooks.entity.spells.thrown_spear.ThrownSpear#m_5790_#1 -->

## Supplementaries

### AbstractMobContainerItem (Type: Item)

- `oneenoughdamage:net/mehvahdjukaar/supplementaries/common/items/abstract_mob_container_item/anger_nearby_entities/1/r` <!-- mode: replace (/r), default: 0.0, DamageType: m_269075, net.mehvahdjukaar.supplementaries.common.items.AbstractMobContainerItem#angerNearbyEntities#1 -->

### BambooSpikesBehavior (Type: Other)

- `oneenoughdamage:net/mehvahdjukaar/supplementaries/integration/create/bamboo_spikes_behavior/damage_entities/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: unknown, net.mehvahdjukaar.supplementaries.integration.create.BambooSpikesBehavior#damageEntities#1 -->

### BambooSpikesBlock (Type: Block)

- `oneenoughdamage:net/mehvahdjukaar/supplementaries/common/block/blocks/bamboo_spikes_block/m_7892/1/r` <!-- mode: replace (/r), default: 1.5, DamageType: bamboospikesblock:get_damage_source, net.mehvahdjukaar.supplementaries.common.block.blocks.BambooSpikesBlock#m_7892_#1 -->

### BombEntity (Type: Other)

- `oneenoughdamage:net/mehvahdjukaar/supplementaries/common/entities/bomb_entity_bomb_type/after_exploded/1/r` <!-- mode: replace (/r), default: 2.0, DamageType: m_269425, net.mehvahdjukaar.supplementaries.common.entities.BombEntity$BombType#afterExploded#1 -->

### BombExplosion (Type: Other)

- `oneenoughdamage:net/mehvahdjukaar/supplementaries/common/misc/explosion/bomb_explosion/m_46061/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: unknown, net.mehvahdjukaar.supplementaries.common.misc.explosion.BombExplosion#m_46061_#1 -->

### CannonBallEntity (Type: Projectile)

- `oneenoughdamage:net/mehvahdjukaar/supplementaries/common/entities/cannon_ball_entity/m_5790/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: unknown, net.mehvahdjukaar.supplementaries.common.entities.CannonBallEntity#m_5790_#1 -->

### FirePitBlock (Type: Block)

- `oneenoughdamage:net/mehvahdjukaar/supplementaries/common/block/blocks/fire_pit_block/m_7892/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: m_269387, net.mehvahdjukaar.supplementaries.common.block.blocks.FirePitBlock#m_7892_#1 -->

### FlammableLiquidBlock (Type: Block)

- `oneenoughdamage:net/mehvahdjukaar/supplementaries/common/fluids/flammable_liquid_block/m_7892/1/r` <!-- mode: replace (/r), default: 1.0, DamageType: m_269387, net.mehvahdjukaar.supplementaries.common.fluids.FlammableLiquidBlock#m_7892_#1 -->

### QuarkCompat (Type: Other)

- `oneenoughdamage:net/mehvahdjukaar/supplementaries/integration/quark_compat/tick_piston/1/r` <!-- mode: replace (/r), default: 1.0, DamageType: unknown, net.mehvahdjukaar.supplementaries.integration.QuarkCompat#tickPiston#1 -->

### SlimeBallEntity (Type: Projectile)

- `oneenoughdamage:net/mehvahdjukaar/supplementaries/common/entities/slime_ball_entity/m_5790/1/r` <!-- mode: replace (/r), default: 0.0, DamageType: m_269390, net.mehvahdjukaar.supplementaries.common.entities.SlimeBallEntity#m_5790_#1 -->

### SlingshotProjectileEntity (Type: Projectile)

- `oneenoughdamage:net/mehvahdjukaar/supplementaries/common/entities/slingshot_projectile_entity/m_5790/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: unknown, net.mehvahdjukaar.supplementaries.common.entities.SlingshotProjectileEntity#m_5790_#1 -->

### ThrowableBrickEntity (Type: Projectile)

- `oneenoughdamage:net/mehvahdjukaar/supplementaries/common/entities/throwable_brick_entity/m_5790/1/r` <!-- mode: replace (/r), default: 1.0, DamageType: m_269390, net.mehvahdjukaar.supplementaries.common.entities.ThrowableBrickEntity#m_5790_#1 -->

### XPBottlingBehavior (Type: Other)

- `oneenoughdamage:net/mehvahdjukaar/supplementaries/common/events/overrides/x_p_bottling_behavior/try_performing_action/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: unknown, net.mehvahdjukaar.supplementaries.common.events.overrides.XPBottlingBehavior#tryPerformingAction#1 -->

## Tacz

### EntityKineticBullet (Type: Projectile)

- `oneenoughdamage:com/tacz/guns/entity/entity_kinetic_bullet/tac_attack_entity/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: unknown, com.tacz.guns.entity.EntityKineticBullet#tacAttackEntity#1 -->
- `oneenoughdamage:com/tacz/guns/entity/entity_kinetic_bullet/tac_attack_entity/2/m` <!-- mode: multiply (/m), default: 1.0, DamageType: unknown, com.tacz.guns.entity.EntityKineticBullet#tacAttackEntity#2 -->

### LuaEntityAccessor (Type: Other)

- `oneenoughdamage:com/tacz/guns/api/util/lua_entity_accessor/hurt/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: m_269264, com.tacz.guns.api.util.LuaEntityAccessor#hurt#1 -->

### ModernKineticGunItem (Type: Item)

- `oneenoughdamage:com/tacz/guns/item/modern_kinetic_gun_item/do_per_living_hurt/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: m_269075, com.tacz.guns.item.ModernKineticGunItem#doPerLivingHurt#1 -->
- `oneenoughdamage:com/tacz/guns/item/modern_kinetic_gun_item/do_per_living_hurt/2/m` <!-- mode: multiply (/m), default: 1.0, DamageType: m_269333, com.tacz.guns.item.ModernKineticGunItem#doPerLivingHurt#2 -->

### ProjectileExplosion (Type: Other)

- `oneenoughdamage:com/tacz/guns/util/block/projectile_explosion/m_46061/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: unknown, com.tacz.guns.util.block.ProjectileExplosion#m_46061_#1 -->

## Tartaricacid

### EntityDanmaku (Type: Projectile)

- `oneenoughdamage:com/github/tartaricacid/touhoulittlemaid/entity/projectile/entity_danmaku/m_5790/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: initdamage:danmaku_damage, com.github.tartaricacid.touhoulittlemaid.entity.projectile.EntityDanmaku#m_5790_#1 -->

## Tetra

### ArcaneFireBlock (Type: Block)

- `oneenoughdamage:se/mickelus/tetra/blocks/arcane_fire_block/m_7892/1/r` <!-- mode: replace (/r), default: 0.5, DamageType: m_269387, se.mickelus.tetra.blocks.ArcaneFireBlock#m_7892_#1 -->

### BleedingPotionEffect (Type: Effect)

- `oneenoughdamage:se/mickelus/tetra/effect/potion/bleeding_potion_effect/m_6742/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: m_269079, se.mickelus.tetra.effect.potion.BleedingPotionEffect#m_6742_#1 -->

### DamageEntityItemEffectOutcome (Type: Other)

- `oneenoughdamage:se/mickelus/tetra/effect/data/outcome/damage_entity_item_effect_outcome/perform/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: m_269079, se.mickelus.tetra.effect.data.outcome.DamageEntityItemEffectOutcome#perform#1 -->

### FocusEffect (Type: Other)

- `oneenoughdamage:se/mickelus/tetra/effect/focus_effect/on_player_tick/1/r` <!-- mode: replace (/r), default: 2.0, DamageType: m_269063, se.mickelus.tetra.effect.FocusEffect#onPlayerTick#1 -->

### ItemEffectHandler (Type: Other)

- `oneenoughdamage:se/mickelus/tetra/effect/item_effect_handler/lambda_on_living_attack_8/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: m_269374, se.mickelus.tetra.effect.ItemEffectHandler#lambda$onLivingAttack$8#1 -->

### ItemModularHandheld (Type: Item)

- `oneenoughdamage:se/mickelus/tetra/items/modular/item_modular_handheld/hit_entity/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: m_269075, se.mickelus.tetra.items.modular.ItemModularHandheld#hitEntity#1 -->

### SweepingEffect (Type: Other)

- `oneenoughdamage:se/mickelus/tetra/effect/sweeping_effect/cause_truesweep_damage/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: unknown, se.mickelus.tetra.effect.SweepingEffect#causeTruesweepDamage#1 -->
- `oneenoughdamage:se/mickelus/tetra/effect/sweeping_effect/lambda_sweep_attack_4/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: unknown, se.mickelus.tetra.effect.SweepingEffect#lambda$sweepAttack$4#1 -->

### ThrownModularItemEntity (Type: Projectile)

- `oneenoughdamage:se/mickelus/tetra/items/modular/thrown_modular_item_entity/m_5790/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: unknown, se.mickelus.tetra.items.modular.ThrownModularItemEntity#m_5790_#1 -->

## Touhou Little Maid

### §6Fire Protect Bauble (§6火焰保护饰品) (Type: Other)

- `oneenoughdamage:com/github/tartaricacid/touhoulittlemaid/entity/item/entity_extinguishing_agent/lambda_damage_fire_immune_monster_0/1/r` <!-- mode: replace (/r), default: 2.0, DamageType: m_269425, com.github.tartaricacid.touhoulittlemaid.entity.item.EntityExtinguishingAgent#lambda$damageFireImmuneMonster$0#1 -->

## Twilightdelight

### RoseTeaItem (Type: Item)

- `oneenoughdamage:dev/xkmc/twilightdelight/content/item/food/rose_tea_item/m_5922/1/r` <!-- mode: replace (/r), default: 4.0, DamageType: unknown, dev.xkmc.twilightdelight.content.item.food.RoseTeaItem#m_5922_#1 -->

## Twilightforest

### Block and Chain (链锤) (Type: Projectile)

- `oneenoughdamage:twilightforest/entity/chain_block/m_5790/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: tfdamagetypes:get_indirect_entity_damage_source, twilightforest.entity.ChainBlock#m_5790_#1 -->

### Block of Fiery Metal (炽铁块) (Type: Block)

- `oneenoughdamage:twilightforest/block/fiery_block/m_141947/1/r` <!-- mode: replace (/r), default: 1.0, DamageType: tfdamagetypes:get_damage_source, twilightforest.block.FieryBlock#m_141947_#1 -->

### Block of Knightmetal (骑士金属块) (Type: Block)

- `oneenoughdamage:twilightforest/block/knightmetal_block/m_7892/1/r` <!-- mode: replace (/r), default: 4.0, DamageType: tfdamagetypes:get_damage_source, twilightforest.block.KnightmetalBlock#m_7892_#1 -->

### Cube of Annihilation (湮灭立方) (Type: Projectile)

- `oneenoughdamage:twilightforest/entity/cube_of_annihilation/m_5790/1/r` <!-- mode: replace (/r), default: 10.0, DamageType: cubeofannihilation:get_damage_source, twilightforest.entity.CubeOfAnnihilation#m_5790_#1 -->

### Enforcement (Type: Other)

- `oneenoughdamage:twilightforest/init/custom/enforcement/lambda_static_8/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: tfdamagetypes:get_damage_source, twilightforest.init.custom.Enforcement#lambda$static$8#1 -->

### EntityUtil (Type: Other)

- `oneenoughdamage:twilightforest/util/entity_util/properly_apply_custom_damage_source/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: unknown, twilightforest.util.EntityUtil#properlyApplyCustomDamageSource#1 -->

### FireJetBlockEntity (Type: Other)

- `oneenoughdamage:twilightforest/block/entity/fire_jet_block_entity/tick_flame/1/r` <!-- mode: replace (/r), default: 2.0, DamageType: tfdamagetypes:get_damage_source, twilightforest.block.entity.FireJetBlockEntity#tickFlame#1 -->

### GhastTrapBlockEntity (Type: Other)

- `oneenoughdamage:twilightforest/block/entity/ghast_trap_block_entity/tick_active/1/r` <!-- mode: replace (/r), default: 7.0, DamageType: m_269264, twilightforest.block.entity.GhastTrapBlockEntity#tickActive#1 -->
- `oneenoughdamage:twilightforest/block/entity/ghast_trap_block_entity/tick_active/2/r` <!-- mode: replace (/r), default: 10.0, DamageType: m_269264, twilightforest.block.entity.GhastTrapBlockEntity#tickActive#2 -->

### GroundAttackGoal (Type: Other)

- `oneenoughdamage:twilightforest/entity/ai/goal/ground_attack_goal/m_8037/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: tfdamagetypes:get_entity_damage_source, twilightforest.entity.ai.goal.GroundAttackGoal#m_8037_#1 -->

### HedgeBlock (Type: Block)

- `oneenoughdamage:twilightforest/block/hedge_block/m_141947/1/r` <!-- mode: replace (/r), default: 3.0, DamageType: m_269325, twilightforest.block.HedgeBlock#m_141947_#1 -->
- `oneenoughdamage:twilightforest/block/hedge_block/m_213897/1/r` <!-- mode: replace (/r), default: 3.0, DamageType: m_269325, twilightforest.block.HedgeBlock#m_213897_#1 -->
- `oneenoughdamage:twilightforest/block/hedge_block/m_6240/1/r` <!-- mode: replace (/r), default: 3.0, DamageType: m_269325, twilightforest.block.HedgeBlock#m_6240_#1 -->
- `oneenoughdamage:twilightforest/block/hedge_block/m_7892/1/r` <!-- mode: replace (/r), default: 3.0, DamageType: m_269325, twilightforest.block.HedgeBlock#m_7892_#1 -->

### HostileMountEvents (Type: Other)

- `oneenoughdamage:twilightforest/events/hostile_mount_events/entity_hurts/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: tfdamagetypes:get_entity_damage_source, twilightforest.events.HostileMountEvents#entityHurts#1 -->

### Hydra Mortar (九头蛇爆弹) (Type: Projectile)

- `oneenoughdamage:twilightforest/entity/boss/hydra_mortar/detonate/1/r` <!-- mode: replace (/r), default: 18.0, DamageType: tfdamagetypes:get_entity_damage_source, twilightforest.entity.boss.HydraMortar#detonate#1 -->

### HydraHeadContainer (Type: Other)

- `oneenoughdamage:twilightforest/entity/boss/hydra_head_container/execute_attacks/1/r` <!-- mode: replace (/r), default: 48.0, DamageType: tfdamagetypes:get_entity_damage_source, twilightforest.entity.boss.HydraHeadContainer#executeAttacks#1 -->
- `oneenoughdamage:twilightforest/entity/boss/hydra_head_container/execute_attacks/2/r` <!-- mode: replace (/r), default: 19.0, DamageType: tfdamagetypes:get_entity_damage_source, twilightforest.entity.boss.HydraHeadContainer#executeAttacks#2 -->

### Lich Bolt (巫妖法束) (Type: Projectile)

- `oneenoughdamage:twilightforest/entity/projectile/lich_bolt/m_5790/1/r` <!-- mode: replace (/r), default: 6.0, DamageType: tfdamagetypes:get_damage_source, twilightforest.entity.projectile.LichBolt#m_5790_#1 -->

### LifedrainScepterItem (Type: Item)

- `oneenoughdamage:twilightforest/item/lifedrain_scepter_item/m_5929/1/r` <!-- mode: replace (/r), default: 1.0, DamageType: tfdamagetypes:get_entity_damage_source, twilightforest.item.LifedrainScepterItem#m_5929_#1 -->
- `oneenoughdamage:twilightforest/item/lifedrain_scepter_item/m_5929/2/r` <!-- mode: replace (/r), default: 3.4028235E38, DamageType: tfdamagetypes:get_entity_damage_source, twilightforest.item.LifedrainScepterItem#m_5929_#2 -->

### Moonworm (月光蠕虫) (Type: Projectile)

- `oneenoughdamage:twilightforest/entity/projectile/moonworm_shot/m_5790/1/r` <!-- mode: replace (/r), default: 0.0, DamageType: unknown, twilightforest.entity.projectile.MoonwormShot#m_5790_#1 -->

### SlideBlock (Type: Entity)

- `oneenoughdamage:twilightforest/entity/slide_block/damage_knockback_entities/1/r` <!-- mode: replace (/r), default: 5.0, DamageType: tfdamagetypes:get_damage_source, twilightforest.entity.SlideBlock#damageKnockbackEntities#1 -->

### SliderBlock (Type: Block)

- `oneenoughdamage:twilightforest/block/slider_block/m_7892/1/r` <!-- mode: replace (/r), default: 5.0, DamageType: tfdamagetypes:get_damage_source, twilightforest.block.SliderBlock#m_7892_#1 -->

### ThornsBlock (Type: Block)

- `oneenoughdamage:twilightforest/block/thorns_block/m_7892/1/r` <!-- mode: replace (/r), default: 4.0, DamageType: tfdamagetypes:get_damage_source, twilightforest.block.ThornsBlock#m_7892_#1 -->

### Thrown Weapon (投掷武器) (Type: Projectile)

- `oneenoughdamage:twilightforest/entity/projectile/thrown_wep/m_5790/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: tfdamagetypes:get_damage_source, twilightforest.entity.projectile.ThrownWep#m_5790_#1 -->

### TwilightWandBolt (Type: Projectile)

- `oneenoughdamage:twilightforest/entity/projectile/twilight_wand_bolt/m_5790/1/r` <!-- mode: replace (/r), default: 6.0, DamageType: tfdamagetypes:get_indirect_entity_damage_source, twilightforest.entity.projectile.TwilightWandBolt#m_5790_#1 -->

## Uranus

### PathingStuckHandler (Type: Other)

- `oneenoughdamage:com/iafenvoy/uranus/object/entity/pathfinding/raycoms/pathing_stuck_handler/complete_stuck_action/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: m_269318, com.iafenvoy.uranus.object.entity.pathfinding.raycoms.PathingStuckHandler#completeStuckAction#1 -->

## Yimeng261

### ChaosBookBauble (Type: Other)

- `oneenoughdamage:com/github/yimeng261/maidspell/item/bauble/chaos_book/chaos_book_bauble/lambda_static_1/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: infodamagesource:damage_source, com.github.yimeng261.maidspell.item.bauble.chaosBook.ChaosBookBauble#lambda$static$1#1 -->
- `oneenoughdamage:com/github/yimeng261/maidspell/item/bauble/chaos_book/chaos_book_bauble/lambda_static_1/2/m` <!-- mode: multiply (/m), default: 1.0, DamageType: unknown, com.github.yimeng261.maidspell.item.bauble.chaosBook.ChaosBookBauble#lambda$static$1#2 -->

### DoubleHeartChainBauble (Type: Other)

- `oneenoughdamage:com/github/yimeng261/maidspell/item/bauble/double_heart_chain/double_heart_chain_bauble/lambda_static_0/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: m_269264, com.github.yimeng261.maidspell.item.bauble.doubleHeartChain.DoubleHeartChainBauble#lambda$static$0#1 -->

### HairpinBauble (Type: Other)

- `oneenoughdamage:com/github/yimeng261/maidspell/item/bauble/hairpin/hairpin_bauble/lambda_static_1/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: unknown, com.github.yimeng261.maidspell.item.bauble.hairpin.HairpinBauble#lambda$static$1#1 -->

### SlashBladeDirectSkillHandler (Type: Other)

- `oneenoughdamage:com/github/yimeng261/maidspell/spell/providers/slashblade/slash_blade_direct_skill_handler/process_pending_direct_skill_hit/1/m` <!-- mode: multiply (/m), default: 1.0, DamageType: m_269333, com.github.yimeng261.maidspell.spell.providers.slashblade.SlashBladeDirectSkillHandler#processPendingDirectSkillHit#1 -->

