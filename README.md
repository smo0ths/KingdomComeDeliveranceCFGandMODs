
#### updated 12/4/2022 :ramen:

###### my config and stuff for kcd hf

###### Use Nvidia Image Scaling and turn down in game res for more fps

#### Create a file in KingdomComeDeliverance/user.cfg and copy paste this and add launch commands (+exec user.cfg -devmode):

---

```python
con_restricted=0;
sys_MaxFPS=162;------def 0------changed to 162*
sys_spec=0;------sets custom spec
sys_spec_GameEffects=3;
sys_spec_Light=3;
sys_spec_ObjectDetail=3;
sys_spec_Particles=3;
sys_spec_Physics=3;
sys_spec_PostProcessing=3;
sys_spec_Shading=3;
sys_spec_Shadows=3;
sys_spec_Sound=3;
sys_spec_Texture=3;
sys_spec_TextureResolution=7;------HD textures on
sys_spec_Vegetation=3;
sys_spec_VolumetricEffects=3;
sys_spec_Water=3;
q_Renderer=3;
q_ShaderFX=3;
q_ShaderGeneral=3;
q_ShaderGlass=3;
q_ShaderHDR=3;
q_ShaderIce=3;
q_ShaderMetal=3;
q_ShaderPostProcess=3;
q_ShaderShadow=3;
q_ShaderSky=3;
q_ShaderTerrain=3;
q_ShaderVegetation=3;
q_ShaderWater=3;
Bind 0 "exec user.cfg";
Bind 8 "g_showHUD 0";
Bind 9 "g_showHUD 1";
Bind f1 "sys_MaxFPS 111";
Bind f2 "sys_MaxFPS 162";
Bind f3 "exec TEST1.cfg";
Bind f4 "exec TEST2.cfg";
cl_fov=73;------def 60------changed to 73*
pl_movement.power_sprint_targetFOV=73;------def 55------changed to 73*
r_DrawNearFOV=73;------def 60------changed to 73*
cl_sensitivity=10;
i_mouse_accel=0;
i_mouse_smooth=0;
g_skipIntro=1;------def 0------changed to 1*
r_Vsync=0;
wh_cs_PlayerLockDisabled=0;------def 0
wh_horse_CameraCentering=0;------def 0.2------changed to 0*
wh_pl_showfirecursor=1;------def 0------changed to 1*
ca_AttachmentCullingRation=300;------def 360------changed to 300*
e_CoverageBufferTerrainLodShift=0;------def 2------changed to 0*
e_CullVegActivation=30;------def 50------changed to 30*
e_DecalsLifeTimeScale=1;------def 2------changed to 1*
e_DecalsRange=10;------def 20------changed to 10*
e_GsmRangeStep=2.5;------def 3------changed to 2.5*
e_LodFaceAreaTargetSize=0.0006;------def 0.001------changed to 0.0006*
e_LodRatio=25;------def 25
e_MergedMeshesInstanceDist=5;------def 8------changed to 5*
e_MergedMeshesLodRatio=1;------def 5------changed to 1*
e_MergedMeshesPool=16384;------def 8192 change to 16384
e_MergedMeshesViewDistRatio=85;------def 70------changed to 85*
e_ObjShadowCastSpec=2;------def 3------changed to 2*
e_PhysProxyTriLimit=5000;------def 10000------changed to 5000*
e_ShadowsBlendCascades=0;------def 2------changed to 0*
e_ShadowsCacheUpdate=1;------def 2------changed to 1*
e_ShadowsCastViewDistRatio=0.8;------def 1------changed to 0.8*
e_ShadowsCastViewDistRatioMulInvis=0.1;------def 0.4------changed to 0.1*
e_ShadowsMaxTexRes=1024;------def 1024
e_ShadowsUpdateViewDistRatio=80;------def 100------changed to 80*
e_SkyQuality=2;------def 2------1 for PERFORMANCE
e_StreamCgfPoolSize=1024;------def 512------changed to 1024*
e_svoTI_SSAOAmount=1.5;------def 1------changed to 1.5*
e_TerrainDetailMaterialsViewDistZ=100;------def 80------changed to 100*
e_TerrainLodRatio=0.5;------def 0.3------changed to 0.5*
e_TerrainOcclusionCullingMaxDist=150;------def 200------changed to 150*
e_UberlodDistanceRatio=1.9;------def 1.8------changed to 1.9*
e_ViewDistRatioVegetation=65;------def 55------changed to 65*
e_VolumetricFog=0;------def 0
es_DebrisLifetimeScale=0.6;------def 1------changed to 0.6*
es_maxphysdistcloth=100;------def 300------changed to 100*
g_breakage_particles_limit=80;------def 160------changed to 80*
gpu_Particle_Physics=0;------def 0
p_max_MC_iters=4000;------def 6000------changed to 4000*
r_AntialiasingMode=3;------def 1------changed to 3*
r_AntialiasingTAAPattern=3;------def 1------changed to 3*
r_AntialiasingTAASharpening=0;------def 0.2------changed to 0*
r_BatchType=1;------def 1
r_DeferredShadingAreaLights=1;------def 1
r_DepthBits=32;------def 24------changed to 32*
r_FogShadowsWater=1;------def 0------changed to 1*
r_HDRBloom=0;------def 1------changed to 0*
r_HDRVignetting=0;------def 1------changed to 0*
r_MotionBlur=0;
r_RainMaxViewDist_Deferred=170;------def 150------changed to 170*
r_ShadowCastingLightsMaxCount=12;------def 16------changed to 12*
r_ShadowsBias=0.00001;------def 0.00008------changed to 0.00001*
r_ShadowsCacheResolutions=6324,4214,2810,1872,624;------def 6324,4214,2810,1872,624
r_ShadowsScreenSpace=1;------def 2------changed to 1*
r_ssdoAmountAmbient=2;------def 1------changed to 2*
r_ssdoAmountDirect=4;------def 1.5------changed to 4*
r_ssdoAmountReflection=5;------def 4------changed to 5*
r_ssdoRadius=1;------def 0.3------changed to 1*
r_ssdoRadiusMin=0.02;------def 0.1------changed to 0.02*
r_SSReflections=0;------def 1------changed to 0*
r_SuperSampling=1;------def 1
r_TexMaxAnisotropy=8;------def 4------changed to 8*
r_TexMinAnisotropy=8;------def 4------changed to 8*
r_TexNoAnisoAlphaTest=0;------def 0------1 for PERFORMANCE
r_VolumetricFogSunLightCorrection=0;------def 1------changed to 0*
r_VolumetricFogTexDepth=8;------def 32------changed to 8*
r_VolumetricFogTexScale=25;------def 10------changed to 25*
r_WaterCaustics=0;------def 1------changed to 0
r_WaterGodRays=0;------def 1------changed to 0
r_WaterReflectionsQuality=3;------def 4------changed to 3*
r_WaterTessellationHW=0;------def 1------changed to 0*
```

---

#### Create a mod folder in KingdomComeDeliverance/Mods

[Cooking cauldron flickering smoke Fix](https://www.nexusmods.com/kingdomcomedeliverance/mods/1177)

[Arrows go fast](https://www.nexusmods.com/kingdomcomedeliverance/mods/1240)

[Remove Those Stupid Trails](https://www.nexusmods.com/kingdomcomedeliverance/mods/7)

[Instant Herb Picking with hand movement](https://www.nexusmods.com/kingdomcomedeliverance/mods/367)

[Alternate Food Spoil (Updated)](https://www.nexusmods.com/kingdomcomedeliverance/mods/1065)

[Inventoried](https://www.nexusmods.com/kingdomcomedeliverance/mods/797)

[Bushes- Collision Remover](https://www.nexusmods.com/kingdomcomedeliverance/mods/591)

[NoTimedDecisions](https://www.nexusmods.com/kingdomcomedeliverance/mods/1343)

[MuttBeQuiet](https://www.nexusmods.com/kingdomcomedeliverance/mods/1322)

[HelmetVision](https://www.nexusmods.com/kingdomcomedeliverance/mods/1337)

[No Helmet Vision](https://www.nexusmods.com/kingdomcomedeliverance/mods/28) (removed)

[No Blood On Screen (make Data folder then add the .pak)](https://www.nexusmods.com/kingdomcomedeliverance/mods/58)

[No Drunk Sharpen Effects (make Data folder then add the .pak)](https://www.nexusmods.com/kingdomcomedeliverance/mods/105)

[No Stamina Visual Effects (make Data folder then add the .pak)](https://www.nexusmods.com/kingdomcomedeliverance/mods/10)

UI edits in KingdomComeDeliverance\Data\GameData.pak\Libs\UI\Textures\Hud_main.dds (make mod folder)

<details><summary>Quicksave (click for edits and link)</summary>
<p>

[Quicksave](https://www.nexusmods.com/kingdomcomedeliverance/mods/1282)

#### replace defaultprofile.xml and edit lines in Quicksave\Data\Data.pak\Libs\Config\defaultprofile.xml

```python
updated to latest KingdomComeDeliverance\Data\patch\ipl_patch_010800.pak\libs\config\defaultprofile.xml
then added:
<action consoleCmd="1" keyboard="f5" name="quicksave" onPress="1" />
under <actionmap name="default" version="22">

also had to add:
<action name="call_horse" onPress="1" onRelease="1"
<action name="horse_dismount" onPress="1" onRelease="1"
the onRelease="1" part after those to fix getting off a horse...
```
</p>
</details>

<details><summary>Ride horse threw rivers (make mod folder)</summary>
<p>

#### zzzz_horse_ignore_water_barrier\Data\zzzz_horse_ignore_water_barrier.pak\Libs\MaterialEffects\SurfaceTypes.xml

```python
add  horse_ignore="1" in here

  <SurfaceType name="mat_deep_water_barrier">
    <Physics friction="0.5" elasticity="0.050000001"  pierceability="11"  dbg_color="123,103,65" horse_ignore="1" />
    <Barrier distance="3" slowdown="1" monologMetaroleId="335"/>
  </SurfaceType>
```
</p>
</details>

---

#### Added all these mods in one rpg_param.xml (make your own so there is no conflicts):

BaseInventoryCapacity set to 999999
<br>
HarmlessFallHeight, InjuringFallHeight and FatalFallHeight set to 9000
<br>
[More Faster XP](https://www.nexusmods.com/kingdomcomedeliverance/mods/1129)
<br>
[Easy Sharpening](https://www.nexusmods.com/kingdomcomedeliverance/mods/336)
<br>
[Ultimate Repair Kit 2.0 Plus](https://www.nexusmods.com/kingdomcomedeliverance/mods/1292)

```python
<?xml version="1.0" encoding="us-ascii"?>
<database name="hammerheart">
  <table name="rpg_param" version="1">
    <header>
      <column name="item_category" type="character varying" />
      <column name="skill_id" type="integer" />
      <column name="perk_id" type="uuid" />
      <column name="rpg_param_key" type="character varying" />
      <column name="rpg_param_value" type="real" />
    </header>
    <rows>
      <row rpg_param_key="BaseInventoryCapacity" rpg_param_value="999999" />
      <row item_category="armor.horse_bridle.*" skill_id="8" />
      <row item_category="armor.horse_saddle.*" skill_id="8" />
      <row rpg_param_key="RepairKitCapacity" rpg_param_value="999999999" />
      <row rpg_param_key="RepairKitItemHealthBestLimit" rpg_param_value="0" />
      <row perk_id="01c3b32a-5751-4c98-b6ab-258d02370382" rpg_param_key="RepairKitCapacity" rpg_param_value="999999999" />
      <row perk_id="01c3b32a-5751-4c98-b6ab-258d02370382" rpg_param_key="RepairKitItemHealthBestLimit" rpg_param_value="0" />
      <row rpg_param_key="AlchemyXPPerSuccessfullBrewing" rpg_param_value="60" />
      <row rpg_param_key="AlchemyXPPerAutocookBrewingRelative" rpg_param_value="0.2" />
      <row rpg_param_key="FactionAngrinessDecayExp" rpg_param_value="3" />
      <row rpg_param_key="HerbGatherXP" rpg_param_value="15" />
      <row rpg_param_key="HorseRidingXPPerDistance" rpg_param_value="18.8" />
      <row rpg_param_key="HoundmasterXPContextCommand" rpg_param_value="3" />
      <row rpg_param_key="HoundmasterXPFeed" rpg_param_value="38" />
      <row rpg_param_key="HoundmasterXPFetch" rpg_param_value="7.5" />
      <row rpg_param_key="HoundmasterXPHit" rpg_param_value="3" />
      <row rpg_param_key="HoundmasterXPKill" rpg_param_value="30" />
      <row rpg_param_key="HoundmasterXPPlay" rpg_param_value="22.5" />
      <row rpg_param_key="HoundmasterXPPOIDiscovery" rpg_param_value="30" />
      <row rpg_param_key="HoundmasterXPPraise" rpg_param_value="22.5" />
      <row rpg_param_key="HunterXPKill" rpg_param_value="22.5" />
      <row rpg_param_key="LockPickingStealthXP" rpg_param_value="12" />
      <row rpg_param_key="LockPickingSuccessXPMulCoef" rpg_param_value="27" />
      <row rpg_param_key="NonSkillBookXP" rpg_param_value="45" />
      <row rpg_param_key="PickpocketingFailXPMod" rpg_param_value="0.5" />
      <row rpg_param_key="PickpocketingStealthXP" rpg_param_value="18" />
      <row rpg_param_key="PickpocketingXP" rpg_param_value="22.5" />
      <row rpg_param_key="ReadingXpPerHour" rpg_param_value="30" />
      <row rpg_param_key="SecondaryStatXPRatio" rpg_param_value="0.8" />
      <row rpg_param_key="SkillXPBlock" rpg_param_value="3" />
      <row rpg_param_key="SkillXPComboHit" rpg_param_value="6" />
      <row rpg_param_key="SkillXPHit" rpg_param_value="3" />
      <row rpg_param_key="SkillXPKill" rpg_param_value="18" />
      <row rpg_param_key="SkillXPPerfectBlock" rpg_param_value="12" />
      <row rpg_param_key="SkillXPRiposte" rpg_param_value="12" />
      <row rpg_param_key="SkillXPUseRepairKit" rpg_param_value="7.5" />
      <row rpg_param_key="StatXPComboHit" rpg_param_value="6" />
      <row rpg_param_key="StatXPHit" rpg_param_value="3" />
      <row rpg_param_key="StatXPKill" rpg_param_value="12" />
      <row rpg_param_key="StatXPSpeechPerSequence" rpg_param_value="2" />
      <row rpg_param_key="StatXPVitalityPerDistance" rpg_param_value="12" />
      <row rpg_param_key="StatXPVitalityPerJump" rpg_param_value="0.8" />
      <row rpg_param_key="StatXPVitalityPerKill" rpg_param_value="22.5" />
      <row rpg_param_key="StatXPVitalityPerVault" rpg_param_value="1.1" />
      <row rpg_param_key="StealthAttackFailXp" rpg_param_value="15" />
      <row rpg_param_key="StealthAttackMaxXp" rpg_param_value="75" />
      <row rpg_param_key="StealthAttackMinXp" rpg_param_value="37.5" />
      <row rpg_param_key="SharpeningMinIdealAngle" rpg_param_value="0" />
      <row rpg_param_key="SharpeningMaxIdealAngle" rpg_param_value="0.98" />
      <row rpg_param_key="SharpeningMinDestructionAngle" rpg_param_value="0.99" />
      <row rpg_param_key="SharpeningMaxDestructionAngle" rpg_param_value="1" />
      <row rpg_param_key="HarmlessFallHeight" rpg_param_value="9000" />
      <row rpg_param_key="InjuringFallHeight" rpg_param_value="9000" />
      <row rpg_param_key="FatalFallHeight" rpg_param_value="9000" />
      <row rpg_param_key="FullClothDirtyingOnFullSpeed" rpg_param_value="5000" />
    </rows>
  </table>
</database>
```

