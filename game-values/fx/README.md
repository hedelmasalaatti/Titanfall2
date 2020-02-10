# FX

## Action

```text
weapon.PlayWeaponEffect
weapon.PlayWeaponEffectNoCull
weapon.StopWeaponEffect
```

```text
projectile.SetImpactEffectTable
projectile.SetModel
projectile.SetProjectilTrailEffectIndex
```

{% tabs %}
{% tab title="Action Target" %}
| Target value | Note |
| :--- | :--- |
| weapon |  |
| projectile |  |
| vortexWeapon |  |
{% endtab %}

{% tab title="Action Command" %}
| Command value | Note |
| :--- | :--- |
| **PlayWeapon** |  |
| PlayWeaponEffect |  |
| PlayWeaponEffectNoCull |  |
| PlayWeaponEffectReturnViewEffectHandle |  |
| PlayImpactFXTable |  |
| StopWeaponEffect |  |
| **PlayFX** |  |
| PlayFXOnEntity |  |
| StopFX |  |
| **Fire** |  |
| FireWeaponBullet |  |
| FireWeaponGrenade |  |
| FireWeaponMissile |  |
| **Projectile** |  |
| StartParticleEffectOnEntity |  |
| StartParticleEffectInWorld\_ReturnEntity |  |
| PlayLoopFXOnEntity |  |
| SetImpactEffectTable |  |
| SetModel |  |
| SetProjectilTrailEffectIndex |  |
{% endtab %}
{% endtabs %}

## Trigger

{% tabs %}
{% tab title="Weapon Trigger" %}
| Trigger name | Note |
| :--- | :--- |
| OnWeaponActivate |  |
| OnWeaponDeactivate |  |
| OnWeaponCustomActivityStart |  |
| OnWeaponPrimaryAttack | Attack player |
| OnWeaponNpcPrimaryAttack | Attack NPC |
| OnWeaponNpcPreAttack | Attack NPC |
| OnWeaponBulletHit | Bullet hit |
| OnWeaponVortexHitBullet | Bullet hit vortex |
| OnWeaponVortexHitProjectile | Bullet hit vortex |
| OnWeaponReadyToFire | Full charge ? |
| OnWeaponChargeLevelIncreased | Charge increase |
| OnWeaponChargeBegin | Charge start |
| OnWeaponChargeEnd | Charge end |
| OnWeaponSustainedDischargeBegin | Charge sustain start |
| OnWeaponSustainedDischargeEnd | Charge sustain end |
| OnWeaponReload | Reload |
| OnWeaponCooldown | Cooldown |
| OnWeaponStartZoomIn | ADS in |
| OnWeaponStartZoomOut | ADS out |
| OnClientAnimEvent |  |
| OnWeaponOwnerChanged |  |
| **Ordnance related** |  |
| OnWeaponAttemptOffhandSwitch |  |
| OnWeaponTossReleaseAnimEvent |  |
| OnWeaponTossPrep |  |
| OnWeaponNpcTossGrenade |  |
| OnWeaponTossCancel | Cancel |
{% endtab %}

{% tab title="Projectile Trigger" %}
| Projectile action name | Note |
| :--- | :--- |
| OnProjectileCollision |  |
| OnProjectileIgnite | Firestar related |
| OnProjectileExplode |  |
{% endtab %}

{% tab title="Ability Trigger" %}
| Ability action name | Note |
| :--- | :--- |
| OnAbilityStart |  |
| OnAbilityEnd |  |
| OnAbilityCharge |  |
| OnAbilityChargeEnd |  |
{% endtab %}
{% endtabs %}

## Attachements

### Weapon Attachements

| Attachement value | Origin | Note |
| :--- | :--- | :--- |
| light\_large | Satchel |  |
| light\_small | Satchel |  |

## Precache

| Precache value | Note |
| :--- | :--- |
| PrecacheParticleSystem |  |
| PrecacheProjectileEntity |  |
| PrecacheImpactEffectTable |  |
| PrecacheHUDMaterial |  |
| PrecacheRes |  |
| PrecacheWeapon |  |
| PrecacheModel |  |
| PrecacheEffect |  |
| PrecacheMaterial |  |
| Minimap\_PrecacheMaterial |  |
