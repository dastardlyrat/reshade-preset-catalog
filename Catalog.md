# ReShade preset catalog

[Effect usage](#effect-usage)

89 presets across 38 game folders. The purpose descriptions are inferred from the enabled effects. Effects are listed in the order recorded in each preset.

## Effect usage

Ranked by the number of desktop presets that enable each technique, out of 89 presets. Technique names are counted once per preset, ignoring capitalization. Different technique names are listed separately.

The ranking excludes AIGX, FineCell, Fine Dream, Fine Illusion, miXSR, BlackWand, CAMERA_OBSCURA, LUNAR_FLOWER, OCCULT, OSCO, GoldenWeave, Twin Lantern, SpiritWorld, BlueSmoke, and FoolsGold. Xenon and the Zenteon techniques are included.

| Enabled technique | Presets |
| --- | ---: |
| `Clarity` | 32 |
| `Vibrance` | 31 |
| `LumaSharpen` | 24 |
| `Tonemap` | 22 |
| `Xenon` | 21 |
| `ZN_LocalContrast` | 16 |
| `DPX` | 13 |
| `MartysMods_MXAO` | 10 |
| `ZenLC` | 10 |
| `HDR` | 9 |
| `uFakeHDR` | 9 |
| `MXAO` | 7 |
| `Quark_LC` | 7 |
| `ZN_SDIL` | 7 |
| `DH_Ambient_Remove` | 6 |
| `Deband` | 5 |
| `DELC_Sharpen` | 5 |
| `MartyMods_Sharpen` | 5 |
| `Blooming_HDR` | 4 |
| `Colourfulness` | 4 |
| `ContrastAdaptiveSharpen` | 4 |
| `MartysMods_Launchpad` | 3 |
| `Clarity2` | 2 |
| `Curves` | 2 |
| `MartysMods_LocalLaplacian` | 2 |
| `PPFXSSDO` | 2 |
| `prod80_01B_RT_Correct_Color` | 2 |
| `SSDO_Plus` | 2 |
| `AdaptiveSharpen` | 1 |
| `ArcaneBloom` | 1 |
| `BASEReFlexAgX` | 1 |
| `Bloom` | 1 |
| `CMAA_2` | 1 |
| `ColorGrading` | 1 |
| `CShade_DLAA` | 1 |
| `Debanding` | 1 |
| `Directionally_Localized_Anti_Aliasing` | 1 |
| `Directionally_Localized_Anti_Aliasing_Plus` | 1 |
| `FGFXLSPOIrr` | 1 |
| `FXAA` | 1 |
| `HDR_Saturation` | 1 |
| `Levels` | 1 |
| `LocalContrastCS` | 1 |
| `MagicBloom` | 1 |
| `MartysMods_AntiAliasing` | 1 |
| `MartysMods_AntiAliasing_Prepass` | 1 |
| `MartysMods_NvidiaSharpen` | 1 |
| `NFAA` | 1 |
| `RM_00_SharedRayFamilyPlatform` | 1 |
| `RM_06_BloomFromSharedRecord` | 1 |
| `SMAA` | 1 |
| `SSAO` | 1 |
| `UFakeHDR2` | 1 |
| `vort_Motion` | 1 |
| `ZenteonFrameWork` | 1 |
| `ZN_DAMPRT_A26` | 1 |

## Atomic Heart

- [HDR Glow and Color Punch.ini](./presets/Atomic%20Heart/HDR%20Glow%20and%20Color%20Punch.ini)
  - **Likely purpose.** HDR Glow and Color Punch, using 6 enabled techniques.
  - **Enabled effects.** `Blooming_HDR@BloomingHDR.fx`, `uFakeHDR@UFakeHDR.fx`, `Clarity@Clarity.fx`, `ZN_LocalContrast@ZN_LC.fx`, `Vibrance@Vibrance.fx`, `Tonemap@Tonemap.fx`

## Baldurs Gate 3

- [Cinematic HDR Color and Fine Detail.ini](./presets/Baldurs%20Gate%203/Cinematic%20HDR%20Color%20and%20Fine%20Detail.ini)
  - **Likely purpose.** Cinematic HDR Color and Fine Detail, using 11 enabled techniques.
  - **Enabled effects.** `Bloom@qUINT_bloom.fx`, `Xenon@Quark_Xenon_Bloom.fx`, `ZN_LocalContrast@ZN_LC.fx`, `Clarity@Clarity.fx`, `DELC_Sharpen@qUINT_sharp.fx`, `LumaSharpen@LumaSharpen.fx`, `HDR@FakeHDR.fx`, `DPX@DPX.fx`, `Tonemap@Tonemap.fx`, `Vibrance@Vibrance.fx`, `ZN_SDIL@ZN_GI.fx`

## Cyberpunk 2077

- [Crisp Color and Local Contrast.ini](./presets/Cyberpunk%202077/Crisp%20Color%20and%20Local%20Contrast.ini)
  - **Likely purpose.** Crisp Color and Local Contrast, using 7 enabled techniques.
  - **Enabled effects.** `Clarity@Clarity.fx`, `DELC_Sharpen@qUINT_sharp.fx`, `LumaSharpen@LumaSharpen.fx`, `Tonemap@Tonemap.fx`, `Vibrance@Vibrance.fx`, `Xenon@Quark_Xenon_Bloom.fx`, `ZN_LocalContrast@ZN_LC.fx`

## DARK SOULS III (C)

- [Illustrated Lighting with Ink and Rich Color.ini](./presets/DARK%20SOULS%20III%20%28C%29/Illustrated%20Lighting%20with%20Ink%20and%20Rich%20Color.ini)
  - **Likely purpose.** Illustrated Lighting with Ink and Rich Color, using 12 enabled techniques.
  - **Enabled effects.** `DPX@DPX.fx`, `LumaSharpen@LumaSharpen.fx`, `Vibrance@Vibrance.fx`, `ContrastAdaptiveSharpen@CAS.fx`, `FineCell_OrganicRichnessColorfulness@FineCell_OrganicRichnessColorfulness.fx`, `FineCell_pRT_AO@FineCell_pRT_AO.fx`, `FineCell_pRT_Cellular_Shader@FineCell_pRT_Cellular_Shader.fx`, `FineCell_pRT_Ink@FineCell_pRT_Ink.fx`, `FineCell_pRT_Richness@FineCell_pRT_Richness.fx`, `FineCell_pRT_Superfine@FineCell_pRT_Superfine.fx`, `FineCell_Cellular_Shader@FineCell_Cellular_Shader.fx`, `FineCell_OrganicGI_RT@FineCell_OrganicGI_RT.fx`
- [Stabilized Ink Detail and Bloom.ini](./presets/DARK%20SOULS%20III%20%28C%29/Stabilized%20Ink%20Detail%20and%20Bloom.ini)
  - **Likely purpose.** Stabilized Ink Detail and Bloom, using 12 enabled techniques.
  - **Enabled effects.** `OSCO_GuidedDetailReclamation@OSCO_GuidedDetailReclamation.fx`, `CAMERA_OBSCURA_StabilizedDetailCaptureV1@CAMERA_OBSCURA_StabilizedDetailCacheV1.fx`, `CAMERA_OBSCURA_StabilizedLumaCaptureV1@CAMERA_OBSCURA_StabilizedLumaCacheV1.fx`, `CAMERA_OBSCURA_StabilizedColorCaptureV1@CAMERA_OBSCURA_StabilizedColorCacheV1.fx`, `OSCO_GuidedInkLines@OSCO_GuidedInkLines.fx`, `OCCULT_lazara@OCCULT_lazara.fx`, `BlackWand_BloomBurst_Corona@BlackWand_14_BloomBurst_Corona.fx`, `BlackWand_EdgeChromaWard@BlackWand_21_EdgeChromaWard.fx`, `CAMERA_OBSCURA_StabilizedColorReapplyV1@CAMERA_OBSCURA_StabilizedColorCacheV1.fx`, `CAMERA_OBSCURA_StabilizedLumaReapplyV1@CAMERA_OBSCURA_StabilizedLumaCacheV1.fx`, `LUNAR_FLOWER_TwinLanternsFullResolutionDualRayAlpha@LUNAR_FLOWER_TwinLanterns_FullResolutionDualRayAlpha.fx`, `CAMERA_OBSCURA_StabilizedDetailReapplyV1@CAMERA_OBSCURA_StabilizedDetailCacheV1.fx`

## DARK SOULS III (Y)

- [Scenery Color and Tone Boost.ini](./presets/DARK%20SOULS%20III%20%28Y%29/Scenery%20Color%20and%20Tone%20Boost.ini)
  - **Likely purpose.** Scenery Color and Tone Boost, using 3 enabled techniques.
  - **Enabled effects.** `Xenon@Zenteon_XenonBloom.fx`, `Tonemap@Tonemap.fx`, `Colourfulness@Colourfulness.fx`

## Deus Ex Mankind Divided

- [Ambient Light Cleanup and Definition.ini](./presets/Deus%20Ex%20Mankind%20Divided/Ambient%20Light%20Cleanup%20and%20Definition.ini)
  - **Likely purpose.** Ambient Light Cleanup and Definition, using 4 enabled techniques.
  - **Enabled effects.** `ZN_SDIL@ZN_GI.fx`, `Clarity@Clarity.fx`, `ZN_LocalContrast@ZN_LC.fx`, `DH_Ambient_Remove@dh_ambient_remove.fx`

## Dying Light 2

- [Lazara Color Recovery and Chromatic Split.ini](./presets/Dying%20Light%202/Lazara%20Color%20Recovery%20and%20Chromatic%20Split.ini)
  - **Likely purpose.** Lazara Color Recovery and Chromatic Split, using one enabled technique.
  - **Enabled effects.** `OCCULT_lazara@OCCULT_lazara.fx`

## ELDEN RING

- [Crisp Detail and Brighter Color.ini](./presets/ELDEN%20RING/Crisp%20Detail%20and%20Brighter%20Color.ini)
  - **Likely purpose.** Crisp Detail and Brighter Color, using 3 enabled techniques.
  - **Enabled effects.** `Clarity@Clarity.fx`, `LumaSharpen@LumaSharpen.fx`, `Vibrance@Vibrance.fx`
- [Deep Shade and Mirage Light with Organic Hatching.ini](./presets/ELDEN%20RING/Deep%20Shade%20and%20Mirage%20Light%20with%20Organic%20Hatching.ini)
  - **Likely purpose.** Deep Shade and Mirage Light with Organic Hatching, using 4 enabled techniques.
  - **Enabled effects.** `fine_dream_deep_shade_Second_Gate@fine_dream_deep_shade_Second_Gate.fx`, `fine_dream_morning_light_Third_Gate@fine_dream_morning_light_Third_Gate.fx`, `fine_dream_mirage_visions_in_light_after_the_Third_Gate@fine_dream_mirage_visions_in_light_after_the_Third_Gate.fx`, `FineCell_AdaptiveHatchSharpenClarity_FibonacciOrganicHatch@FineCell_AdaptiveHatchSharpenClarity_FibonacciOrganicHatch.fx`
- [Delirium Fog Mask and Highlight Shield.ini](./presets/ELDEN%20RING/Delirium%20Fog%20Mask%20and%20Highlight%20Shield.ini)
  - **Likely purpose.** Delirium Fog Mask and Highlight Shield, using one enabled technique.
  - **Enabled effects.** `fine_illusion_shared_mask_orchestrator@fine_illusion_shared_mask_orchestrator.fx`
- [Fantasy Color and Ambient Shadow Depth.ini](./presets/ELDEN%20RING/Fantasy%20Color%20and%20Ambient%20Shadow%20Depth.ini)
  - **Likely purpose.** Fantasy Color and Ambient Shadow Depth, using 9 enabled techniques.
  - **Enabled effects.** `ZN_SDIL@ZN_GI.fx`, `DH_Ambient_Remove@dh_ambient_remove.fx`, `MartysMods_MXAO@MartysMods_MXAO.fx`, `Clarity@Clarity.fx`, `LumaSharpen@LumaSharpen.fx`, `Vibrance@Vibrance.fx`, `Quark_LC@Quark_Local_Contrast.fx`, `Tonemap@Tonemap.fx`, `Deband@Deband.fx`
- [Fantasy HDR Color and Smooth Gradients.ini](./presets/ELDEN%20RING/Fantasy%20HDR%20Color%20and%20Smooth%20Gradients.ini)
  - **Likely purpose.** Fantasy HDR Color and Smooth Gradients, using 5 enabled techniques.
  - **Enabled effects.** `LumaSharpen@LumaSharpen.fx`, `HDR@FakeHDR.fx`, `Tonemap@Tonemap.fx`, `Vibrance@Vibrance.fx`, `Deband@Deband.fx`
- [Fantasy HDR with Deep Shadows - No Downsample.ini](./presets/ELDEN%20RING/Fantasy%20HDR%20with%20Deep%20Shadows%20-%20No%20Downsample.ini)
  - **Likely purpose.** Fantasy HDR with Deep Shadows, using 15 enabled techniques.
  - **Enabled effects.** `MartysMods_Launchpad@MartysMods_LAUNCHPAD.fx`, `LumaSharpen@LumaSharpen.fx`, `Clarity@Clarity.fx`, `SSAO@SSAO.fx`, `MartysMods_MXAO@MartysMods_MXAO.fx`, `MXAO@qUINT_mxao.fx`, `uFakeHDR@UFakeHDR.fx`, `ZN_LocalContrast@ZN_LC.fx`, `HDR@FakeHDR.fx`, `Quark_LC@Quark_Local_Contrast.fx`, `Tonemap@Tonemap.fx`, `Vibrance@Vibrance.fx`, `DPX@DPX.fx`, `Xenon@Quark_Xenon_Bloom.fx`, `Deband@Deband.fx`
- [Fine Dream Day-Night Relighting - ES-xGI.ini](./presets/ELDEN%20RING/Fine%20Dream%20Day-Night%20Relighting%20-%20ES-xGI.ini)
  - **Likely purpose.** Fine Dream Day-Night Relighting, using 6 enabled techniques.
  - **Enabled effects.** `fine_dream_respect_light_and_shadow_The_First_Gate@fine_dream_respect_light_and_shadow_The_First_Gate.fx`, `fine_dream_night_and_sun_Garden_After_the_First_Gate@fine_dream_night_and_sun_Garden_After_the_First_Gate.fx`, `fine_dream_deep_shade_Second_Gate@fine_dream_deep_shade_Second_Gate.fx`, `fine_dream_gloom_the_night_after_the_second_gate@fine_dream_gloom_the_night_after_the_second_gate.fx`, `fine_dream_morning_light_Third_Gate@fine_dream_morning_light_Third_Gate.fx`, `fine_dream_miday_sun_Repose_After_the_Third_Gate@fine_dream_miday_sun_Repose_After_the_Third_Gate.fx`
- [Fine Dream Shadow to Golden Light - Elden Final.ini](./presets/ELDEN%20RING/Fine%20Dream%20Shadow%20to%20Golden%20Light%20-%20Elden%20Final.ini)
  - **Likely purpose.** Fine Dream Shadow to Golden Light, using 6 enabled techniques.
  - **Enabled effects.** `fine_dream_night_and_sun_Garden_After_the_First_Gate@fine_dream_night_and_sun_Garden_After_the_First_Gate.fx`, `fine_dream_deep_shade_Second_Gate@fine_dream_deep_shade_Second_Gate.fx`, `fine_dream_gloom_the_night_after_the_second_gate@fine_dream_gloom_the_night_after_the_second_gate.fx`, `fine_dream_morning_light_Third_Gate@fine_dream_morning_light_Third_Gate.fx`, `fine_dream_mirage_visions_in_light_after_the_Third_Gate@fine_dream_mirage_visions_in_light_after_the_Third_Gate.fx`, `fine_dream_vision_of_gold_after_the_Fourth_Gate_visions_of_the_Fifth_Gate@fine_dream_vision_of_gold_after_the_Fourth_Gate_visions_of_the_Fifth_Gate.fx`
- [Fine Dream Shadow to Golden Light - Style 7F.ini](./presets/ELDEN%20RING/Fine%20Dream%20Shadow%20to%20Golden%20Light%20-%20Style%207F.ini)
  - **Likely purpose.** Fine Dream Shadow to Golden Light, using 6 enabled techniques.
  - **Enabled effects.** `fine_dream_night_and_sun_Garden_After_the_First_Gate@fine_dream_night_and_sun_Garden_After_the_First_Gate.fx`, `fine_dream_deep_shade_Second_Gate@fine_dream_deep_shade_Second_Gate.fx`, `fine_dream_gloom_the_night_after_the_second_gate@fine_dream_gloom_the_night_after_the_second_gate.fx`, `fine_dream_morning_light_Third_Gate@fine_dream_morning_light_Third_Gate.fx`, `fine_dream_mirage_visions_in_light_after_the_Third_Gate@fine_dream_mirage_visions_in_light_after_the_Third_Gate.fx`, `fine_dream_vision_of_gold_after_the_Fourth_Gate_visions_of_the_Fifth_Gate@fine_dream_vision_of_gold_after_the_Fourth_Gate_visions_of_the_Fifth_Gate.fx`
- [Fine Dream Shadow to Mirage Light - XCOM2 Variant.ini](./presets/ELDEN%20RING/Fine%20Dream%20Shadow%20to%20Mirage%20Light%20-%20XCOM2%20Variant.ini)
  - **Likely purpose.** Fine Dream Shadow to Mirage Light, using 6 enabled techniques.
  - **Enabled effects.** `fine_dream_night_and_sun_Garden_After_the_First_Gate@fine_dream_night_and_sun_Garden_After_the_First_Gate.fx`, `fine_dream_deep_shade_Second_Gate@fine_dream_deep_shade_Second_Gate.fx`, `fine_dream_gloom_the_night_after_the_second_gate@fine_dream_gloom_the_night_after_the_second_gate.fx`, `fine_dream_morning_light_Third_Gate@fine_dream_morning_light_Third_Gate.fx`, `fine_dream_mirage_visions_in_light_after_the_Third_Gate@fine_dream_mirage_visions_in_light_after_the_Third_Gate.fx`, `fine_dream_Wake_No_Longer_Dreaming_The_Fourth_Gate@fine_dream_Wake_No_Longer_Dreaming_The_Fourth_Gate.fx`
- [FineCell Scenery Indirect Light and Occlusion.ini](./presets/ELDEN%20RING/FineCell%20Scenery%20Indirect%20Light%20and%20Occlusion.ini)
  - **Likely purpose.** FineCell Scenery Indirect Light and Occlusion, using one enabled technique.
  - **Enabled effects.** `FineCell_GIAO@FineCell_GIAO.fx`
- [Fog-Aware Hand-Drawn Cel Shading.ini](./presets/ELDEN%20RING/Fog-Aware%20Hand-Drawn%20Cel%20Shading.ini)
  - **Likely purpose.** Fog-Aware Hand-Drawn Cel Shading, using 4 enabled techniques.
  - **Enabled effects.** `AIGX_Respect_FogDetector_Tap55@AIGX_Respect_FogDetector_Tap55.fx`, `AIGX_Basic_OrganicHatch@AIGX_Basic_OrganicHatch.fx`, `RT_FineCelSSR_Basic_InkEdges@RT_FineCelSSR_Basic_InkEdges.fx`, `RT_FineCelSSR_Basic_Cel@RT_FineCelSSR_Basic_Cel.fx`
- [Hand-Drawn Cel Shading.ini](./presets/ELDEN%20RING/Hand-Drawn%20Cel%20Shading.ini)
  - **Likely purpose.** Hand-Drawn Cel Shading, using 3 enabled techniques.
  - **Enabled effects.** `RT_FineCelSSR_Basic_Cel@RT_FineCelSSR_Basic_Cel.fx`, `RT_FineCelSSR_Basic_InkEdges@RT_FineCelSSR_Basic_InkEdges.fx`, `AIGX_Basic_OrganicHatch@AIGX_Basic_OrganicHatch.fx`
- [HDR Color and Shadow Depth - Standard Screen.ini](./presets/ELDEN%20RING/HDR%20Color%20and%20Shadow%20Depth%20-%20Standard%20Screen.ini)
  - **Likely purpose.** HDR Color and Shadow Depth, using 13 enabled techniques.
  - **Enabled effects.** `MartyMods_Sharpen@MartysMods_SHARPEN.fx`, `Clarity@Clarity.fx`, `LumaSharpen@LumaSharpen.fx`, `Quark_LC@Quark_Local_Contrast.fx`, `ZN_LocalContrast@ZN_LC.fx`, `Tonemap@Tonemap.fx`, `Vibrance@Vibrance.fx`, `DPX@DPX.fx`, `Xenon@Quark_Xenon_Bloom.fx`, `uFakeHDR@UFakeHDR.fx`, `HDR@FakeHDR.fx`, `MXAO@qUINT_mxao.fx`, `MartysMods_MXAO@MartysMods_MXAO.fx`
- [HDR Color and Smooth Gradients - Theatre Screen.ini](./presets/ELDEN%20RING/HDR%20Color%20and%20Smooth%20Gradients%20-%20Theatre%20Screen.ini)
  - **Likely purpose.** HDR Color and Smooth Gradients, using 12 enabled techniques.
  - **Enabled effects.** `MartyMods_Sharpen@MartysMods_SHARPEN.fx`, `uFakeHDR@UFakeHDR.fx`, `MartysMods_Launchpad@MartysMods_LAUNCHPAD.fx`, `LumaSharpen@LumaSharpen.fx`, `Clarity@Clarity.fx`, `Xenon@Quark_Xenon_Bloom.fx`, `MartysMods_MXAO@MartysMods_MXAO.fx`, `MXAO@qUINT_mxao.fx`, `ZN_LocalContrast@ZN_LC.fx`, `Tonemap@Tonemap.fx`, `Vibrance@Vibrance.fx`, `Deband@Deband.fx`
- [Immersive Color Grading and Shadow Detail.ini](./presets/ELDEN%20RING/Immersive%20Color%20Grading%20and%20Shadow%20Detail.ini)
  - **Likely purpose.** Immersive Color Grading and Shadow Detail, using 11 enabled techniques.
  - **Enabled effects.** `ZN_SDIL@ZN_GI.fx`, `MartysMods_Launchpad@MartysMods_LAUNCHPAD.fx`, `ZN_LocalContrast@ZN_LC.fx`, `MartysMods_MXAO@MartysMods_MXAO.fx`, `Clarity@Clarity.fx`, `LumaSharpen@LumaSharpen.fx`, `MartyMods_Sharpen@MartysMods_SHARPEN.fx`, `DELC_Sharpen@qUINT_sharp.fx`, `Vibrance@Vibrance.fx`, `ColorGrading@ColorGrading.fx`, `Quark_LC@Quark_Local_Contrast.fx`
- [Lazara Fog-Aware Relighting with Bloom and Ink.ini](./presets/ELDEN%20RING/Lazara%20Fog-Aware%20Relighting%20with%20Bloom%20and%20Ink.ini)
  - **Likely purpose.** Lazara Fog-Aware Relighting with Bloom and Ink, using 18 enabled techniques.
  - **Enabled effects.** `CAMERA_OBSCURA_StabilizedColorCaptureV1@CAMERA_OBSCURA_StabilizedColorCacheV1.fx`, `CAMERA_OBSCURA_StabilizedLumaCaptureV1@CAMERA_OBSCURA_StabilizedLumaCacheV1.fx`, `CAMERA_OBSCURA_StabilizedDetailCaptureV1@CAMERA_OBSCURA_StabilizedDetailCacheV1.fx`, `BlackWand_FogLight_Guard@BlackWand_10_FogLight_Guard.fx`, `BlackWand_MicroDetail_Clarity@BlackWand_12_MicroDetail_Clarity.fx`, `BlackWand_ToneDetail_Richness@BlackWand_07_ToneDetail_Richness.fx`, `GoldenWeave_RMGI_Redux@GoldenWeave_RMGI_Redux.fx`, `BlackWand_BloomBurst_Corona@BlackWand_14_BloomBurst_Corona.fx`, `BlackWand_GI_ColorBleed@BlackWand_05_GI_ColorBleed.fx`, `FoolsGold@FoolsGold.fx`, `OSCO_GuidedDetailReclamation@OSCO_GuidedDetailReclamation.fx`, `OCCULT_lazara@OCCULT_lazara.fx`, `CAMERA_OBSCURA_ExternalImageDenoiseV1@CAMERA_OBSCURA_ExternalImageDenoiseV1.fx`, `CAMERA_OBSCURA_StabilizedLumaReapplyV1@CAMERA_OBSCURA_StabilizedLumaCacheV1.fx`, `CAMERA_OBSCURA_StabilizedColorReapplyV1@CAMERA_OBSCURA_StabilizedColorCacheV1.fx`, `CAMERA_OBSCURA_StabilizedDetailReapplyV1@CAMERA_OBSCURA_StabilizedDetailCacheV1.fx`, `BlackWand_EdgeChromaWard@BlackWand_21_EdgeChromaWard.fx`, `OSCO_GuidedInkLines@OSCO_GuidedInkLines.fx`
- [Light Color and Saturation Boost.ini](./presets/ELDEN%20RING/Light%20Color%20and%20Saturation%20Boost.ini)
  - **Likely purpose.** Light Color and Saturation Boost, using 3 enabled techniques.
  - **Enabled effects.** `Vibrance@Vibrance.fx`, `Colourfulness@Colourfulness.fx`, `Xenon@Zenteon_XenonBloom.fx`
- [Motion Emphasis and Sharpened Lighting.ini](./presets/ELDEN%20RING/Motion%20Emphasis%20and%20Sharpened%20Lighting.ini)
  - **Likely purpose.** Motion Emphasis and Sharpened Lighting, using 5 enabled techniques.
  - **Enabled effects.** `vort_Motion@vort_Motion.fx`, `ContrastAdaptiveSharpen@CAS.fx`, `Levels@Levels.fx`, `ZN_DAMPRT_A26@ZN_DAMP_RT.fx`, `FGFXLSPOIrr@FGFXLargeScalePerceptualObscuranceIrradiance.fx`
- [Organic Indirect Light and Gloss.ini](./presets/ELDEN%20RING/Organic%20Indirect%20Light%20and%20Gloss.ini)
  - **Likely purpose.** Organic Indirect Light and Gloss, using 2 enabled techniques.
  - **Enabled effects.** `fine_dream_organic_ray_marched_Global_Illumination@fine_dream_organic_ray_marched_Global_Illumination.fx`, `fine_dream_organic_ray_marched_gloss@fine_dream_organic_ray_marched_gloss.fx`

## Ghost of a Tale

- [Cinematic Tone and Crisp Detail.ini](./presets/Ghost%20of%20a%20Tale/Cinematic%20Tone%20and%20Crisp%20Detail.ini)
  - **Likely purpose.** Cinematic Tone and Crisp Detail, using 6 enabled techniques.
  - **Enabled effects.** `Clarity@Clarity.fx`, `Curves@Curves.fx`, `DELC_Sharpen@qUINT_sharp.fx`, `DPX@DPX.fx`, `LumaSharpen@LumaSharpen.fx`, `Tonemap@Tonemap.fx`

## Ghost of Tsushima DIRECTOR'S CUT

- [Ambient Light Cleanup with Sharpened HDR Color.ini](./presets/Ghost%20of%20Tsushima%20DIRECTOR%27S%20CUT/Ambient%20Light%20Cleanup%20with%20Sharpened%20HDR%20Color.ini)
  - **Likely purpose.** Ambient Light Cleanup with Sharpened HDR Color, using 7 enabled techniques.
  - **Enabled effects.** `DH_Ambient_Remove@dh_ambient_remove.fx`, `Clarity@Clarity.fx`, `MartysMods_NvidiaSharpen@MartysMods_NVSHARPEN.fx`, `LumaSharpen@LumaSharpen.fx`, `Xenon@Quark_Xenon_Bloom.fx`, `Vibrance@Vibrance.fx`, `uFakeHDR@UFakeHDR.fx`

## Gothic 1 Remake

- [Masked Deep Tones and Organic Indirect Light.ini](./presets/Gothic%201%20Remake/Masked%20Deep%20Tones%20and%20Organic%20Indirect%20Light.ini)
  - **Likely purpose.** Masked Deep Tones and Organic Indirect Light, using 3 enabled techniques.
  - **Enabled effects.** `miXSR_FC_shared_mask_orchestrator@miXSR_FC_shared_mask_orchestrator.fx`, `miXSR_FC_bio_deep_tone@miXSR_FC_bio_deep_tone.fx`, `fine_dream_bio_raym_global_illumination@fine_dream_bio_raym_global_illumination.fx`

## HardWest2

- [Cinematic HDR Color with Smoother Edges.ini](./presets/HardWest2/Cinematic%20HDR%20Color%20with%20Smoother%20Edges.ini)
  - **Likely purpose.** Cinematic HDR Color with Smoother Edges, using 8 enabled techniques.
  - **Enabled effects.** `Clarity@Clarity.fx`, `DPX@DPX.fx`, `HDR@FakeHDR.fx`, `Xenon@Quark_Xenon_Bloom.fx`, `SMAA@SMAA.fx`, `Tonemap@Tonemap.fx`, `Vibrance@Vibrance.fx`, `ZN_LocalContrast@ZN_LC.fx`

## Hell Is Us

- [Edge Smoothing Prepass.ini](./presets/Hell%20Is%20Us/Edge%20Smoothing%20Prepass.ini)
  - **Likely purpose.** Edge Smoothing Prepass, using one enabled technique.
  - **Enabled effects.** `MartysMods_AntiAliasing_Prepass@MartysMods_SMAA.fx`
- [Glossy Ink Illustration with Indirect Lighting.ini](./presets/Hell%20Is%20Us/Glossy%20Ink%20Illustration%20with%20Indirect%20Lighting.ini)
  - **Likely purpose.** Glossy Ink Illustration with Indirect Lighting, using 9 enabled techniques.
  - **Enabled effects.** `FineCell_SurfaceSheen@FineCell_SurfaceSheen.fx`, `FineCell_OrganicRichnessColorfulness@FineCell_OrganicRichnessColorfulness.fx`, `FineCell_Bloom@FineCell_Bloom.fx`, `FineCell_OrganicGI_RT@FineCell_OrganicGI_RT.fx`, `FineCell_pRT_Richness@FineCell_pRT_Richness.fx`, `FineCell_pRT_AO@FineCell_pRT_AO.fx`, `FineCell_Cellular_Shader@FineCell_Cellular_Shader.fx`, `FineCell_pRT_Superfine@FineCell_pRT_Superfine.fx`, `FineCell_InkEdges@FineCell_InkEdges.fx`
- [Ink and Hatch Illustration with Directional Lighting.ini](./presets/Hell%20Is%20Us/Ink%20and%20Hatch%20Illustration%20with%20Directional%20Lighting.ini)
  - **Likely purpose.** Ink and Hatch Illustration with Directional Lighting, using 8 enabled techniques.
  - **Enabled effects.** `BlackWand_SmartAA_EdgeClean@BlackWand_01_SmartAA_EdgeClean.fx`, `BlackWand_ToneDetail_Richness@BlackWand_07_ToneDetail_Richness.fx`, `SpiritWorld@SpiritWorld.fx`, `BlackWand_HatchInkCel@BlackWand_04_HatchInkCel.fx`, `BlackWand_FarZ_Detail@BlackWand_11_FarZ_Detail.fx`, `GoldenWeave_RMGI_Redux@GoldenWeave_RMGI_Redux.fx`, `BlackWand_GuidedDirectional_TonalShade@BlackWand_17_GuidedDirectional_TonalShade.fx`, `BlueSmoke@BlueSmoke.fx`
- [Local Contrast and HDR Color Boost.ini](./presets/Hell%20Is%20Us/Local%20Contrast%20and%20HDR%20Color%20Boost.ini)
  - **Likely purpose.** Local Contrast and HDR Color Boost, using 5 enabled techniques.
  - **Enabled effects.** `Clarity@Clarity.fx`, `ZenLC@Zenteon_LocalContrast.fx`, `Vibrance@Vibrance.fx`, `Xenon@Zenteon_XenonBloom.fx`, `uFakeHDR@uFakeHDR.fx`

## Jedi Survivor

- [Local Contrast and Color Lift.ini](./presets/Jedi%20Survivor/Local%20Contrast%20and%20Color%20Lift.ini)
  - **Likely purpose.** Local Contrast and Color Lift, using 5 enabled techniques.
  - **Enabled effects.** `Clarity@Clarity.fx`, `Xenon@Quark_Xenon_Bloom.fx`, `ZN_LocalContrast@ZN_LC.fx`, `Vibrance@Vibrance.fx`, `Vibrance@Vibrance.fx`

## KingdomComeDeliverance2

- [Cinematic Color and Local Definition.ini](./presets/KingdomComeDeliverance2/Cinematic%20Color%20and%20Local%20Definition.ini)
  - **Likely purpose.** Cinematic Color and Local Definition, using 3 enabled techniques.
  - **Enabled effects.** `Clarity@Clarity.fx`, `DPX@DPX.fx`, `ZenLC@Zenteon_LocalContrast.fx`

## Legend of Grimrock 2

- [Dungeon Glow and Deep Shadows with Clean Edges.ini](./presets/Legend%20of%20Grimrock%202/Dungeon%20Glow%20and%20Deep%20Shadows%20with%20Clean%20Edges.ini)
  - **Likely purpose.** Dungeon Glow and Deep Shadows with Clean Edges, using 16 enabled techniques.
  - **Enabled effects.** `MagicBloom@MagicBloom.fx`, `Vibrance@Vibrance.fx`, `Colourfulness@Colourfulness.fx`, `Clarity@Clarity.fx`, `LumaSharpen@LumaSharpen.fx`, `MartysMods_MXAO@MartysMods_MXAO.fx`, `HDR@FakeHDR.fx`, `MXAO@qUINT_mxao.fx`, `SSDO_Plus@GloomAO.fx`, `FXAA@FXAA.fx`, `DPX@DPX.fx`, `CMAA_2@CMAA_2.fx`, `Blooming_HDR@BloomingHDR.fx`, `Tonemap@Tonemap.fx`, `ContrastAdaptiveSharpen@CAS.fx`, `AdaptiveSharpen@AdaptiveSharpen.fx`

## Lords of the Fallen

- [Scenery Relighting and Smooth Color Gradients.ini](./presets/Lords%20of%20the%20Fallen/Scenery%20Relighting%20and%20Smooth%20Color%20Gradients.ini)
  - **Likely purpose.** Scenery Relighting and Smooth Color Gradients, using 9 enabled techniques.
  - **Enabled effects.** `DH_Ambient_Remove@dh_ambient_remove.fx`, `ZN_SDIL@ZN_GI.fx`, `MartysMods_LocalLaplacian@MartysMods_LOCALLAPLACIAN.fx`, `Deband@Deband.fx`, `Quark_LC@Quark_Local_Contrast.fx`, `MartysMods_MXAO@MartysMods_MXAO.fx`, `Tonemap@Tonemap.fx`, `Colourfulness@Colourfulness.fx`, `Vibrance@Vibrance.fx`

## MGS_TPP

- [Tactical Shadow Depth and Clean Edges.ini](./presets/MGS_TPP/Tactical%20Shadow%20Depth%20and%20Clean%20Edges.ini)
  - **Likely purpose.** Tactical Shadow Depth and Clean Edges, using 14 enabled techniques.
  - **Enabled effects.** `LumaSharpen@LumaSharpen.fx`, `ZN_LocalContrast@ZN_LC.fx`, `LocalContrastCS@LocalContrastCS.fx`, `Clarity2@Clarity2.fx`, `Xenon@Quark_Xenon_Bloom.fx`, `Quark_LC@Quark_Local_Contrast.fx`, `PPFXSSDO@PPFX_SSDO.fx`, `MartysMods_MXAO@MartysMods_MXAO.fx`, `MXAO@qUINT_mxao.fx`, `SSDO_Plus@GloomAO.fx`, `CShade_DLAA@cDLAA.fx`, `MartyMods_Sharpen@MartysMods_SHARPEN.fx`, `Vibrance@Vibrance.fx`, `Tonemap@Tonemap.fx`
- [Tactical Shadow Depth and Smooth Gradients - Simple.ini](./presets/MGS_TPP/Tactical%20Shadow%20Depth%20and%20Smooth%20Gradients%20-%20Simple.ini)
  - **Likely purpose.** Tactical Shadow Depth and Smooth Gradients, using 10 enabled techniques.
  - **Enabled effects.** `LumaSharpen@LumaSharpen.fx`, `Clarity2@Clarity2.fx`, `Xenon@Quark_Xenon_Bloom.fx`, `PPFXSSDO@PPFX_SSDO.fx`, `MXAO@qUINT_mxao.fx`, `MartyMods_Sharpen@MartysMods_SHARPEN.fx`, `Vibrance@Vibrance.fx`, `Tonemap@Tonemap.fx`, `ZN_LocalContrast@ZN_LC.fx`, `Debanding@qUINT_deband.fx`

## Miasma

- [HDR Tone and Clarity.ini](./presets/Miasma/HDR%20Tone%20and%20Clarity.ini)
  - **Likely purpose.** HDR Tone and Clarity, using 3 enabled techniques.
  - **Enabled effects.** `Clarity@Clarity.fx`, `uFakeHDR@UFakeHDR.fx`, `Xenon@Zenteon_XenonBloom.fx`

## NoRestForTheWicked

- [Soft Bloom and Rich Color with Clean Edges.ini](./presets/NoRestForTheWicked/Soft%20Bloom%20and%20Rich%20Color%20with%20Clean%20Edges.ini)
  - **Likely purpose.** Soft Bloom and Rich Color with Clean Edges, using 9 enabled techniques.
  - **Enabled effects.** `Directionally_Localized_Anti_Aliasing_Plus@DLAA_Plus.fx`, `Clarity@Clarity.fx`, `LumaSharpen@LumaSharpen.fx`, `HDR_Saturation@HDRSaturation.fx`, `Quark_LC@Quark_Local_Contrast.fx`, `Tonemap@Tonemap.fx`, `Vibrance@Vibrance.fx`, `ZN_LocalContrast@ZN_LC.fx`, `ArcaneBloom@ArcaneBloom.fx`

## Oblivion Remastered

- [HDR Glow and Rich Color.ini](./presets/Oblivion%20Remastered/HDR%20Glow%20and%20Rich%20Color.ini)
  - **Likely purpose.** HDR Glow and Rich Color, using 7 enabled techniques.
  - **Enabled effects.** `ZenLC@Zenteon_LocalContrast.fx`, `Clarity@Clarity.fx`, `Vibrance@Vibrance.fx`, `Blooming_HDR@BloomingHDR.fx`, `Xenon@Zenteon_XenonBloom.fx`, `HDR@FakeHDR.fx`, `Tonemap@Tonemap.fx`

## ofAshAndSteel

- [Texture Definition and Color Lift.ini](./presets/ofAshAndSteel/Texture%20Definition%20and%20Color%20Lift.ini)
  - **Likely purpose.** Texture Definition and Color Lift, using 6 enabled techniques.
  - **Enabled effects.** `Clarity@Clarity.fx`, `LumaSharpen@LumaSharpen.fx`, `MartysMods_LocalLaplacian@MartysMods_LOCALLAPLACIAN.fx`, `Vibrance@Vibrance.fx`, `ZenLC@Zenteon_LocalContrast.fx`, `Tonemap@Tonemap.fx`

## Phantom Brigade

- [Lazara Color Recovery and Stable Sharpness.ini](./presets/Phantom%20Brigade/Lazara%20Color%20Recovery%20and%20Stable%20Sharpness.ini)
  - **Likely purpose.** Lazara Color Recovery and Stable Sharpness, using 2 enabled techniques.
  - **Enabled effects.** `OCCULT_lazara@OCCULT_lazara.fx`, `OCCULT_RM_StabilityGuidedSharpness@OCCULT_RM_StabilityGuidedSharpness.fx`

## PhantomDoctrine

- [Ambient Light Cleanup and Crisp Color.ini](./presets/PhantomDoctrine/Ambient%20Light%20Cleanup%20and%20Crisp%20Color.ini)
  - **Likely purpose.** Ambient Light Cleanup and Crisp Color, using 4 enabled techniques.
  - **Enabled effects.** `Clarity@Clarity.fx`, `LumaSharpen@LumaSharpen.fx`, `DH_Ambient_Remove@dh_ambient_remove.fx`, `Vibrance@Vibrance.fx`

## Phoenix Point

- [Cinematic HDR Color and Tactical Edge Cleanup.ini](./presets/Phoenix%20Point/Cinematic%20HDR%20Color%20and%20Tactical%20Edge%20Cleanup.ini)
  - **Likely purpose.** Cinematic HDR Color and Tactical Edge Cleanup, using 10 enabled techniques.
  - **Enabled effects.** `Clarity@Clarity.fx`, `Tonemap@Tonemap.fx`, `ZenLC@Zenteon_LocalContrast.fx`, `Xenon@Zenteon_XenonBloom.fx`, `LumaSharpen@LumaSharpen.fx`, `Directionally_Localized_Anti_Aliasing@DLAA_Plus.fx`, `DPX@DPX.fx`, `NFAA@NFAA.fx`, `uFakeHDR@UFakeHDR.fx`, `Vibrance@Vibrance.fx`
- [Rich Indirect Lighting with Bloom and Surface Sheen.ini](./presets/Phoenix%20Point/Rich%20Indirect%20Lighting%20with%20Bloom%20and%20Surface%20Sheen.ini)
  - **Likely purpose.** Rich Indirect Lighting with Bloom and Surface Sheen, using 6 enabled techniques.
  - **Enabled effects.** `FineCell_xRT_AO@FineCell_xRT_AO.fx`, `FineCell_xRT_Richness@FineCell_xRT_Richness.fx`, `FineCell_OrganicGI_RT@FineCell_OrganicGI_RT.fx`, `FineCell_Bloom@FineCell_Bloom.fx`, `FineCell_SurfaceSheen@FineCell_SurfaceSheen.fx`, `FineCell_OrganicRichnessColorfulness@FineCell_OrganicRichnessColorfulness.fx`

## Prey

- [Ambient Relighting with Color Correction and Detail.ini](./presets/Prey/Ambient%20Relighting%20with%20Color%20Correction%20and%20Detail.ini)
  - **Likely purpose.** Ambient Relighting with Color Correction and Detail, using 7 enabled techniques.
  - **Enabled effects.** `DH_Ambient_Remove@dh_ambient_remove.fx`, `ZN_SDIL@ZN_GI.fx`, `prod80_01B_RT_Correct_Color@PD80_01B_RT_Correct_Color.fx`, `MartysMods_MXAO@MartysMods_MXAO.fx`, `LumaSharpen@LumaSharpen.fx`, `Clarity@Clarity.fx`, `ContrastAdaptiveSharpen@CAS.fx`

## Red Dead Redemption 2

- [Color Lift and Local Contrast.ini](./presets/Red%20Dead%20Redemption%202/Color%20Lift%20and%20Local%20Contrast.ini)
  - **Likely purpose.** Color Lift and Local Contrast, using 2 enabled techniques.
  - **Enabled effects.** `Vibrance@Vibrance.fx`, `ZenLC@Zenteon_LocalContrast.fx`

## Remnant2

- [Lazara Color Recovery with Denoised Detail.ini](./presets/Remnant2/Lazara%20Color%20Recovery%20with%20Denoised%20Detail.ini)
  - **Likely purpose.** Lazara Color Recovery with Denoised Detail, using 5 enabled techniques.
  - **Enabled effects.** `CAMERA_OBSCURA_ExternalImageDenoiseV1@CAMERA_OBSCURA_ExternalImageDenoiseV1.fx`, `OSCO_GuidedDetailReclamation@OSCO_GuidedDetailReclamation.fx`, `CAMERA_OBSCURA_StabilizedDetailCaptureV1@CAMERA_OBSCURA_StabilizedDetailCacheV1.fx`, `OCCULT_lazara@OCCULT_lazara.fx`, `CAMERA_OBSCURA_StabilizedDetailReapplyV1@CAMERA_OBSCURA_StabilizedDetailCacheV1.fx`

## Rise of the Tomb Raider

- [Deep Shadow Illustration with Hatch Detail.ini](./presets/Rise%20of%20the%20Tomb%20Raider/Deep%20Shadow%20Illustration%20with%20Hatch%20Detail.ini)
  - **Likely purpose.** Deep Shadow Illustration with Hatch Detail, using 4 enabled techniques.
  - **Enabled effects.** `fine_dream_deep_shade_Second_Gate@fine_dream_deep_shade_Second_Gate.fx`, `fine_dream_night_and_sun_Garden_After_the_First_Gate@fine_dream_night_and_sun_Garden_After_the_First_Gate.fx`, `fine_dream_gloom_the_night_after_the_second_gate@fine_dream_gloom_the_night_after_the_second_gate.fx`, `fine_dream_hatch_clarity@fine_dream_hatch_clarity.fx`
- [Denoised Ink Illustration and Reflections - AMD RDNA1 Quality.ini](./presets/Rise%20of%20the%20Tomb%20Raider/Denoised%20Ink%20Illustration%20and%20Reflections%20-%20AMD%20RDNA1%20Quality.ini)
  - **Likely purpose.** Denoised Ink Illustration and Reflections, using 9 enabled techniques.
  - **Enabled effects.** `FineCell_xRT_AO_RDNA1@Base/RDNA1/FineCell_xRT_AO_RDNA1.fx`, `FineCell_Organic_xRTAO_RDNA1@Base/RDNA1/FineCell_Organic_xRTAO_RDNA1.fx`, `FineCell_xRT_SSR_RDNA1@Base/RDNA1/FineCell_xRT_SSR_RDNA1.fx`, `FineCell_xRT_Cellular_Shader_RDNA1@Base/RDNA1/FineCell_xRT_Cellular_Shader_RDNA1.fx`, `FineCell_xRT_Ink_RDNA1@Base/RDNA1/FineCell_xRT_Ink_RDNA1.fx`, `FineCell_xRT_Richness_RDNA1@Base/RDNA1/FineCell_xRT_Richness_RDNA1.fx`, `FineCell_xRT_Superfine_RDNA1@Base/RDNA1/FineCell_xRT_Superfine_RDNA1.fx`, `Fine_Cell_Temporal_Fibonacci_Denoiser@Fine_Cell_Temporal_Fibonacci_Denoiser.fx`, `Fine_Cell_Generic_Fibonacci_Denoiser@Fine_Cell_Generic_Fibonacci_Denoiser.fx`
- [Denoised Ink Illustration and Reflections - AMD RDNA2 Plus Quality.ini](./presets/Rise%20of%20the%20Tomb%20Raider/Denoised%20Ink%20Illustration%20and%20Reflections%20-%20AMD%20RDNA2%20Plus%20Quality.ini)
  - **Likely purpose.** Denoised Ink Illustration and Reflections, using 9 enabled techniques.
  - **Enabled effects.** `FineCell_xRT_AO_RDNA2plus@RDNA2plus/FineCell_xRT_AO_RDNA2plus.fx`, `FineCell_Organic_xRTAO_RDNA2plus@RDNA2plus/FineCell_Organic_xRTAO_RDNA2plus.fx`, `FineCell_xRT_SSR_RDNA2plus@RDNA2plus/FineCell_xRT_SSR_RDNA2plus.fx`, `FineCell_xRT_Cellular_Shader_RDNA2plus@RDNA2plus/FineCell_xRT_Cellular_Shader_RDNA2plus.fx`, `FineCell_xRT_Ink_RDNA2plus@RDNA2plus/FineCell_xRT_Ink_RDNA2plus.fx`, `FineCell_xRT_Richness_RDNA2plus@RDNA2plus/FineCell_xRT_Richness_RDNA2plus.fx`, `FineCell_xRT_Superfine_RDNA2plus@RDNA2plus/FineCell_xRT_Superfine_RDNA2plus.fx`, `Fine_Cell_Temporal_Fibonacci_Denoiser@Fine_Cell_Temporal_Fibonacci_Denoiser.fx`, `Fine_Cell_Generic_Fibonacci_Denoiser@Fine_Cell_Generic_Fibonacci_Denoiser.fx`
- [Denoised Ink Illustration and Reflections - AMD RDNA2 Plus Template.ini](./presets/Rise%20of%20the%20Tomb%20Raider/Denoised%20Ink%20Illustration%20and%20Reflections%20-%20AMD%20RDNA2%20Plus%20Template.ini)
  - **Likely purpose.** Denoised Ink Illustration and Reflections, using 9 enabled techniques.
  - **Enabled effects.** `FineCell_xRT_AO@FineCell_xRT_AO.fx`, `FineCell_Organic_xRTAO@FineCell_Organic_xRTAO.fx`, `FineCell_xRT_SSR@FineCell_xRT_SSR.fx`, `FineCell_xRT_Cellular_Shader@FineCell_xRT_Cellular_Shader.fx`, `FineCell_xRT_Ink@FineCell_xRT_Ink.fx`, `FineCell_xRT_Richness@FineCell_xRT_Richness.fx`, `FineCell_xRT_Superfine@FineCell_xRT_Superfine.fx`, `Fine_Cell_Temporal_Fibonacci_Denoiser@Fine_Cell_Temporal_Fibonacci_Denoiser.fx`, `Fine_Cell_Generic_Fibonacci_Denoiser@Fine_Cell_Generic_Fibonacci_Denoiser.fx`
- [Denoised Ink Illustration and Reflections - NVIDIA Turing Plus Template.ini](./presets/Rise%20of%20the%20Tomb%20Raider/Denoised%20Ink%20Illustration%20and%20Reflections%20-%20NVIDIA%20Turing%20Plus%20Template.ini)
  - **Likely purpose.** Denoised Ink Illustration and Reflections, using 9 enabled techniques.
  - **Enabled effects.** `FineCell_xRT_AO@FineCell_xRT_AO.fx`, `FineCell_Organic_xRTAO@FineCell_Organic_xRTAO.fx`, `FineCell_xRT_SSR@FineCell_xRT_SSR.fx`, `FineCell_xRT_Cellular_Shader@FineCell_xRT_Cellular_Shader.fx`, `FineCell_xRT_Ink@FineCell_xRT_Ink.fx`, `FineCell_xRT_Richness@FineCell_xRT_Richness.fx`, `FineCell_xRT_Superfine@FineCell_xRT_Superfine.fx`, `Fine_Cell_Temporal_Fibonacci_Denoiser@Fine_Cell_Temporal_Fibonacci_Denoiser.fx`, `Fine_Cell_Generic_Fibonacci_Denoiser@Fine_Cell_Generic_Fibonacci_Denoiser.fx`
- [Ink Illustration and Contact Shadows - AMD RDNA1 Performance.ini](./presets/Rise%20of%20the%20Tomb%20Raider/Ink%20Illustration%20and%20Contact%20Shadows%20-%20AMD%20RDNA1%20Performance.ini)
  - **Likely purpose.** Ink Illustration and Contact Shadows, using 7 enabled techniques.
  - **Enabled effects.** `FineCell_xRT_AO_RDNA1@Base/RDNA1/FineCell_xRT_AO_RDNA1.fx`, `FineCell_Organic_xRTAO_RDNA1@Base/RDNA1/FineCell_Organic_xRTAO_RDNA1.fx`, `FineCell_xRT_Cellular_Shader_RDNA1@Base/RDNA1/FineCell_xRT_Cellular_Shader_RDNA1.fx`, `FineCell_xRT_Ink_RDNA1@Base/RDNA1/FineCell_xRT_Ink_RDNA1.fx`, `FineCell_xRT_Richness_RDNA1@Base/RDNA1/FineCell_xRT_Richness_RDNA1.fx`, `FineCell_xRT_Superfine_RDNA1@Base/RDNA1/FineCell_xRT_Superfine_RDNA1.fx`, `Fine_Cell_Temporal_Fibonacci_Denoiser@Fine_Cell_Temporal_Fibonacci_Denoiser.fx`
- [Ink Illustration and Contact Shadows - AMD RDNA2 Plus Performance.ini](./presets/Rise%20of%20the%20Tomb%20Raider/Ink%20Illustration%20and%20Contact%20Shadows%20-%20AMD%20RDNA2%20Plus%20Performance.ini)
  - **Likely purpose.** Ink Illustration and Contact Shadows, using 7 enabled techniques.
  - **Enabled effects.** `FineCell_xRT_AO_RDNA2plus@RDNA2plus/FineCell_xRT_AO_RDNA2plus.fx`, `FineCell_Organic_xRTAO_RDNA2plus@RDNA2plus/FineCell_Organic_xRTAO_RDNA2plus.fx`, `FineCell_xRT_Cellular_Shader_RDNA2plus@RDNA2plus/FineCell_xRT_Cellular_Shader_RDNA2plus.fx`, `FineCell_xRT_Ink_RDNA2plus@RDNA2plus/FineCell_xRT_Ink_RDNA2plus.fx`, `FineCell_xRT_Richness_RDNA2plus@RDNA2plus/FineCell_xRT_Richness_RDNA2plus.fx`, `FineCell_xRT_Superfine_RDNA2plus@RDNA2plus/FineCell_xRT_Superfine_RDNA2plus.fx`, `Fine_Cell_Temporal_Fibonacci_Denoiser@Fine_Cell_Temporal_Fibonacci_Denoiser.fx`
- [Ink Illustration and Reflections - AMD RDNA1 Balanced.ini](./presets/Rise%20of%20the%20Tomb%20Raider/Ink%20Illustration%20and%20Reflections%20-%20AMD%20RDNA1%20Balanced.ini)
  - **Likely purpose.** Ink Illustration and Reflections, using 8 enabled techniques.
  - **Enabled effects.** `FineCell_xRT_AO_RDNA1@Base/RDNA1/FineCell_xRT_AO_RDNA1.fx`, `FineCell_Organic_xRTAO_RDNA1@Base/RDNA1/FineCell_Organic_xRTAO_RDNA1.fx`, `FineCell_xRT_SSR_RDNA1@Base/RDNA1/FineCell_xRT_SSR_RDNA1.fx`, `FineCell_xRT_Cellular_Shader_RDNA1@Base/RDNA1/FineCell_xRT_Cellular_Shader_RDNA1.fx`, `FineCell_xRT_Ink_RDNA1@Base/RDNA1/FineCell_xRT_Ink_RDNA1.fx`, `FineCell_xRT_Richness_RDNA1@Base/RDNA1/FineCell_xRT_Richness_RDNA1.fx`, `FineCell_xRT_Superfine_RDNA1@Base/RDNA1/FineCell_xRT_Superfine_RDNA1.fx`, `Fine_Cell_Temporal_Fibonacci_Denoiser@Fine_Cell_Temporal_Fibonacci_Denoiser.fx`
- [Ink Illustration and Reflections - AMD RDNA1 Template.ini](./presets/Rise%20of%20the%20Tomb%20Raider/Ink%20Illustration%20and%20Reflections%20-%20AMD%20RDNA1%20Template.ini)
  - **Likely purpose.** Ink Illustration and Reflections, using 5 enabled techniques.
  - **Enabled effects.** `FineCell_xRT_SSR@FineCell_xRT_SSR.fx`, `FineCell_xRT_Cellular_Shader@FineCell_xRT_Cellular_Shader.fx`, `FineCell_xRT_Ink@FineCell_xRT_Ink.fx`, `FineCell_xRT_Richness@FineCell_xRT_Richness.fx`, `FineCell_xRT_Superfine@FineCell_xRT_Superfine.fx`
- [Ink Illustration and Reflections - AMD RDNA2 Plus Balanced.ini](./presets/Rise%20of%20the%20Tomb%20Raider/Ink%20Illustration%20and%20Reflections%20-%20AMD%20RDNA2%20Plus%20Balanced.ini)
  - **Likely purpose.** Ink Illustration and Reflections, using 8 enabled techniques.
  - **Enabled effects.** `FineCell_xRT_AO_RDNA2plus@RDNA2plus/FineCell_xRT_AO_RDNA2plus.fx`, `FineCell_Organic_xRTAO_RDNA2plus@RDNA2plus/FineCell_Organic_xRTAO_RDNA2plus.fx`, `FineCell_xRT_SSR_RDNA2plus@RDNA2plus/FineCell_xRT_SSR_RDNA2plus.fx`, `FineCell_xRT_Cellular_Shader_RDNA2plus@RDNA2plus/FineCell_xRT_Cellular_Shader_RDNA2plus.fx`, `FineCell_xRT_Ink_RDNA2plus@RDNA2plus/FineCell_xRT_Ink_RDNA2plus.fx`, `FineCell_xRT_Richness_RDNA2plus@RDNA2plus/FineCell_xRT_Richness_RDNA2plus.fx`, `FineCell_xRT_Superfine_RDNA2plus@RDNA2plus/FineCell_xRT_Superfine_RDNA2plus.fx`, `Fine_Cell_Temporal_Fibonacci_Denoiser@Fine_Cell_Temporal_Fibonacci_Denoiser.fx`
- [Mirage Lighting with Stabilized Organic Hatching.ini](./presets/Rise%20of%20the%20Tomb%20Raider/Mirage%20Lighting%20with%20Stabilized%20Organic%20Hatching.ini)
  - **Likely purpose.** Mirage Lighting with Stabilized Organic Hatching, using 3 enabled techniques.
  - **Enabled effects.** `fine_dream_night_and_sun_Garden_After_the_First_Gate@fine_dream_night_and_sun_Garden_After_the_First_Gate.fx`, `fine_dream_mirage_visions_in_light_after_the_Third_Gate@fine_dream_mirage_visions_in_light_after_the_Third_Gate.fx`, `fine_dream_organic_hatch_TAA@fine_dream_organic_hatch_TAA.fx`

## S.T.A.L.K.E.R. 2 Heart of Chornobyl

- [Local Contrast and Color Definition.ini](./presets/S.T.A.L.K.E.R.%202%20Heart%20of%20Chornobyl/Local%20Contrast%20and%20Color%20Definition.ini)
  - **Likely purpose.** Local Contrast and Color Definition, using 4 enabled techniques.
  - **Enabled effects.** `ZenteonFrameWork@Zenteon_Framework.fx`, `ZenLC@Zenteon_LocalContrast.fx`, `Clarity@Clarity.fx`, `Vibrance@Vibrance.fx`

## Sekiro

- [Cinematic HDR Color and Shadow Depth.ini](./presets/Sekiro/Cinematic%20HDR%20Color%20and%20Shadow%20Depth.ini)
  - **Likely purpose.** Cinematic HDR Color and Shadow Depth, using 8 enabled techniques.
  - **Enabled effects.** `Clarity@Clarity.fx`, `ZN_LocalContrast@ZN_LC.fx`, `HDR@FakeHDR.fx`, `DPX@DPX.fx`, `Tonemap@Tonemap.fx`, `Vibrance@Vibrance.fx`, `ZN_SDIL@ZN_GI.fx`, `MXAO@qUINT_mxao.fx`

## Tainted Grail FoA

- [Corrected Cinematic Color and Contact Shadows.ini](./presets/Tainted%20Grail%20FoA/Corrected%20Cinematic%20Color%20and%20Contact%20Shadows.ini)
  - **Likely purpose.** Corrected Cinematic Color and Contact Shadows, using 7 enabled techniques.
  - **Enabled effects.** `Vibrance@Vibrance.fx`, `prod80_01B_RT_Correct_Color@PD80_01B_RT_Correct_Color.fx`, `Xenon@Zenteon_XenonBloom.fx`, `MartysMods_MXAO@MartysMods_MXAO.fx`, `DPX@DPX.fx`, `Clarity@Clarity.fx`, `ZenLC@Zenteon_LocalContrast.fx`

## The Surge

- [Bloom and Cinematic Tone with Crisp Detail.ini](./presets/The%20Surge/Bloom%20and%20Cinematic%20Tone%20with%20Crisp%20Detail.ini)
  - **Likely purpose.** Bloom and Cinematic Tone with Crisp Detail, using 6 enabled techniques.
  - **Enabled effects.** `DELC_Sharpen@qUINT_sharp.fx`, `Clarity@Clarity.fx`, `LumaSharpen@LumaSharpen.fx`, `DPX@DPX.fx`, `Curves@Curves.fx`, `Blooming_HDR@BloomingHDR.fx`

## The Surge 2

- [HDR Tone and Clean Edges.ini](./presets/The%20Surge%202/HDR%20Tone%20and%20Clean%20Edges.ini)
  - **Likely purpose.** HDR Tone and Clean Edges, using 4 enabled techniques.
  - **Enabled effects.** `UFakeHDR@uFakeHDR.fx`, `Xenon@Zenteon_XenonBloom.fx`, `ZenLC@Zenteon_LocalContrast.fx`, `MartysMods_AntiAliasing@MartysMods_SMAA.fx`

## The Witcher 3

- [Crisp Texture and Local Contrast - DX12.ini](./presets/The%20Witcher%203/Crisp%20Texture%20and%20Local%20Contrast%20-%20DX12.ini)
  - **Likely purpose.** Crisp Texture and Local Contrast, using 4 enabled techniques.
  - **Enabled effects.** `Clarity@Clarity.fx`, `LumaSharpen@LumaSharpen.fx`, `Xenon@Quark_Xenon_Bloom.fx`, `ZN_LocalContrast@ZN_LC.fx`

## Warhammer 40,000 Rogue Trader

- [Crisp Tactical Color and Tone.ini](./presets/Warhammer%2040%2C000%20Rogue%20Trader/Crisp%20Tactical%20Color%20and%20Tone.ini)
  - **Likely purpose.** Crisp Tactical Color and Tone, using 4 enabled techniques.
  - **Enabled effects.** `Clarity@Clarity.fx`, `Tonemap@Tonemap.fx`, `Vibrance@Vibrance.fx`, `LumaSharpen@LumaSharpen.fx`
- [HDR Tactical Color and Local Contrast.ini](./presets/Warhammer%2040%2C000%20Rogue%20Trader/HDR%20Tactical%20Color%20and%20Local%20Contrast.ini)
  - **Likely purpose.** HDR Tactical Color and Local Contrast, using 6 enabled techniques.
  - **Enabled effects.** `Xenon@Zenteon_XenonBloom.fx`, `Clarity@Clarity.fx`, `ZenLC@Zenteon_LocalContrast.fx`, `Vibrance@Vibrance.fx`, `UFakeHDR2@uFakeHDR.fx`, `HDR@FakeHDR.fx`

## Wolfenstein.The.New.Order

- [Cinematic Grading and Sharpened Contrast.ini](./presets/Wolfenstein.The.New.Order/Cinematic%20Grading%20and%20Sharpened%20Contrast.ini)
  - **Likely purpose.** Cinematic Grading and Sharpened Contrast, using 6 enabled techniques.
  - **Enabled effects.** `Clarity@Clarity.fx`, `LumaSharpen@LumaSharpen.fx`, `ZN_LocalContrast@ZN_LC.fx`, `Xenon@Quark_Xenon_Bloom.fx`, `Tonemap@Tonemap.fx`, `DPX@DPX.fx`

## XCOM 2

- [AgX Tone and Stabilized Twin Lantern Relighting.ini](./presets/XCOM%202/AgX%20Tone%20and%20Stabilized%20Twin%20Lantern%20Relighting.ini)
  - **Likely purpose.** AgX Tone and Stabilized Twin Lantern Relighting, using 12 enabled techniques.
  - **Enabled effects.** `OSCO_GuidedDetailReclamation@OSCO_GuidedDetailReclamation.fx`, `BASEReFlexAgX@FlexAgX_transmigrated.fx`, `CAMERA_OBSCURA_StabilizedLumaCaptureV1@CAMERA_OBSCURA_StabilizedLumaCacheV1.fx`, `GoldenWeave_RMGI_Redux@GoldenWeave_RMGI_Redux.fx`, `OCCULT_lazara@OCCULT_lazara.fx`, `CAMERA_OBSCURA_TwinLantern@CAMERA_OBSCURA_TwinLantern.fx`, `LUNAR_FLOWER_TwinLanternsFidelityOverdrive@LUNAR_FLOWER_TwinLanterns_FidelityOverdrive.fx`, `CAMERA_OBSCURA_StabilizedColorCaptureV1@CAMERA_OBSCURA_StabilizedColorCacheV1.fx`, `CAMERA_OBSCURA_StabilizedDetailCaptureV1@CAMERA_OBSCURA_StabilizedDetailCacheV1.fx`, `CAMERA_OBSCURA_StabilizedColorReapplyV1@CAMERA_OBSCURA_StabilizedColorCacheV1.fx`, `CAMERA_OBSCURA_StabilizedLumaReapplyV1@CAMERA_OBSCURA_StabilizedLumaCacheV1.fx`, `CAMERA_OBSCURA_StabilizedDetailReapplyV1@CAMERA_OBSCURA_StabilizedDetailCacheV1.fx`
- [Black Glass Reflections and Smooth Edges - Style 16A.ini](./presets/XCOM%202/Black%20Glass%20Reflections%20and%20Smooth%20Edges%20-%20Style%2016A.ini)
  - **Likely purpose.** Black Glass Reflections and Smooth Edges, using 7 enabled techniques.
  - **Enabled effects.** `fine_illusion_shared_mask_orchestrator@fine_illusion_shared_mask_orchestrator.fx`, `FineCell_SurfaceSheen@FineCell_SurfaceSheen.fx`, `fine_illusion_gloss_material_response@fine_illusion_gloss_material_response.fx`, `fine_illusion_obsidian_black_glass_ssr_gloss@fine_illusion_obsidian_black_glass_ssr_gloss.fx`, `fine_illusion_USLAA@fine_illusion_USLAA.fx`, `fine_illusion_USLAA_Adjunct@fine_illusion_USLAA_Adjunct.fx`, `fine_illusion_USLAA_Adjunct_Reinforcement@fine_illusion_USLAA_Adjunct_Reinforcement.fx`
- [Black Glass Reflections with Indirect Light and Color Enrichment.ini](./presets/XCOM%202/Black%20Glass%20Reflections%20with%20Indirect%20Light%20and%20Color%20Enrichment.ini)
  - **Likely purpose.** Black Glass Reflections with Indirect Light and Color Enrichment, using 10 enabled techniques.
  - **Enabled effects.** `fine_illusion_shared_mask_orchestrator@fine_illusion_shared_mask_orchestrator.fx`, `FineCell_SurfaceSheen@FineCell_SurfaceSheen.fx`, `fine_illusion_gloss_material_response@fine_illusion_gloss_material_response.fx`, `fine_illusion_obsidian_black_glass_ssr_gloss@fine_illusion_obsidian_black_glass_ssr_gloss.fx`, `fine_illusion_USLAA@fine_illusion_USLAA.fx`, `fine_illusion_USLAA_Adjunct@fine_illusion_USLAA_Adjunct.fx`, `fine_illusion_USLAA_Adjunct_Reinforcement@fine_illusion_USLAA_Adjunct_Reinforcement.fx`, `fine_illusion_organic_fibonacci_fxaa_smaa@fine_illusion_organic_fibonacci_fxaa_smaa.fx`, `FineCell_OrganicGI_RT@FineCell_OrganicGI_RT.fx`, `fine_illusion_color_theory_scheme_enricher@fine_illusion_color_theory_scheme_enricher.fx`
- [Dual-Ray Lighting - Low Strength.ini](./presets/XCOM%202/Dual-Ray%20Lighting%20-%20Low%20Strength.ini)
  - **Likely purpose.** Dual-Ray Lighting, using one enabled technique.
  - **Enabled effects.** `LUNAR_FLOWER_TwinLanternsFullResolutionDualRayAlpha@LUNAR_FLOWER_TwinLanterns_FullResolutionDualRayAlpha.fx`
- [Fine Dream Tactical Shadow and Mirage Lighting.ini](./presets/XCOM%202/Fine%20Dream%20Tactical%20Shadow%20and%20Mirage%20Lighting.ini)
  - **Likely purpose.** Fine Dream Tactical Shadow and Mirage Lighting, using 6 enabled techniques.
  - **Enabled effects.** `fine_dream_night_and_sun_Garden_After_the_First_Gate@fine_dream_night_and_sun_Garden_After_the_First_Gate.fx`, `fine_dream_deep_shade_Second_Gate@fine_dream_deep_shade_Second_Gate.fx`, `fine_dream_gloom_the_night_after_the_second_gate@fine_dream_gloom_the_night_after_the_second_gate.fx`, `fine_dream_morning_light_Third_Gate@fine_dream_morning_light_Third_Gate.fx`, `fine_dream_mirage_visions_in_light_after_the_Third_Gate@fine_dream_mirage_visions_in_light_after_the_Third_Gate.fx`, `fine_dream_Wake_No_Longer_Dreaming_The_Fourth_Gate@fine_dream_Wake_No_Longer_Dreaming_The_Fourth_Gate.fx`
- [Fog-Aware Tactical Relighting from Gloom to Sun.ini](./presets/XCOM%202/Fog-Aware%20Tactical%20Relighting%20from%20Gloom%20to%20Sun.ini)
  - **Likely purpose.** Fog-Aware Tactical Relighting from Gloom to Sun, using 9 enabled techniques.
  - **Enabled effects.** `fine_dream_Fog_Gate_and_Light_Shield_The_First_Gate@fine_dream_Fog_Gate_and_Light_Shield_The_First_Gate.fx`, `fine_dream_night_and_sun_Garden_After_the_First_Gate@fine_dream_night_and_sun_Garden_After_the_First_Gate.fx`, `fine_dream_deep_shade_Second_Gate@fine_dream_deep_shade_Second_Gate.fx`, `fine_dream_gloom_the_night_after_the_second_gate@fine_dream_gloom_the_night_after_the_second_gate.fx`, `fine_dream_morning_light_Third_Gate@fine_dream_morning_light_Third_Gate.fx`, `fine_dream_Wake_No_Longer_Dreaming_The_Fourth_Gate@fine_dream_Wake_No_Longer_Dreaming_The_Fourth_Gate.fx`, `fine_dream_balanced_shadow_richness_lift@fine_dream_balanced_shadow_richness_lift.fx`, `fine_dream_miday_sun_Repose_After_the_Third_Gate@fine_dream_miday_sun_Repose_After_the_Third_Gate.fx`, `fine_dream_mirage_visions_in_light_after_the_Third_Gate@fine_dream_mirage_visions_in_light_after_the_Third_Gate.fx`
- [Fog-Shielded Shadow and Mirage Lighting - Style 30A.ini](./presets/XCOM%202/Fog-Shielded%20Shadow%20and%20Mirage%20Lighting%20-%20Style%2030A.ini)
  - **Likely purpose.** Fog-Shielded Shadow and Mirage Lighting, using 4 enabled techniques.
  - **Enabled effects.** `fine_dream_Fog_Gate_and_Light_Shield_The_First_Gate@fine_dream_Fog_Gate_and_Light_Shield_The_First_Gate.fx`, `fine_dream_deep_shade_Second_Gate@fine_dream_deep_shade_Second_Gate.fx`, `fine_dream_morning_light_Third_Gate@fine_dream_morning_light_Third_Gate.fx`, `fine_dream_mirage_visions_in_light_after_the_Third_Gate@fine_dream_mirage_visions_in_light_after_the_Third_Gate.fx`
- [Hatched Ink Cel Shading.ini](./presets/XCOM%202/Hatched%20Ink%20Cel%20Shading.ini)
  - **Likely purpose.** Hatched Ink Cel Shading, using one enabled technique.
  - **Enabled effects.** `BlackWand_HatchInkCel@BlackWand_04_HatchInkCel.fx`
- [Lazara Color Recovery with Temporal Denoising.ini](./presets/XCOM%202/Lazara%20Color%20Recovery%20with%20Temporal%20Denoising.ini)
  - **Likely purpose.** Lazara Color Recovery with Temporal Denoising, using 2 enabled techniques.
  - **Enabled effects.** `OCCULT_lazara@OCCULT_lazara.fx`, `CAMERA_OBSCURA_TwinLanternTL08TemporalDenoiseStandalone@CAMERA_OBSCURA_TwinLanternTL08TemporalDenoiseStandalone.fx`
- [Lazara Fog-Aware Dual-Ray Lighting and Detail Recovery.ini](./presets/XCOM%202/Lazara%20Fog-Aware%20Dual-Ray%20Lighting%20and%20Detail%20Recovery.ini)
  - **Likely purpose.** Lazara Fog-Aware Dual-Ray Lighting and Detail Recovery, using 10 enabled techniques.
  - **Enabled effects.** `OSCO_GuidedDetailReclamation@OSCO_GuidedDetailReclamation.fx`, `BlackWand_FogLight_Guard@BlackWand_10_FogLight_Guard.fx`, `CAMERA_OBSCURA_StabilizedDetailCaptureV1@CAMERA_OBSCURA_StabilizedDetailCacheV1.fx`, `CAMERA_OBSCURA_StabilizedLumaCaptureV1@CAMERA_OBSCURA_StabilizedLumaCacheV1.fx`, `CAMERA_OBSCURA_StabilizedColorCaptureV1@CAMERA_OBSCURA_StabilizedColorCacheV1.fx`, `OCCULT_lazara@OCCULT_lazara.fx`, `CAMERA_OBSCURA_StabilizedLumaReapplyV1@CAMERA_OBSCURA_StabilizedLumaCacheV1.fx`, `CAMERA_OBSCURA_StabilizedColorReapplyV1@CAMERA_OBSCURA_StabilizedColorCacheV1.fx`, `CAMERA_OBSCURA_StabilizedDetailReapplyV1@CAMERA_OBSCURA_StabilizedDetailCacheV1.fx`, `LUNAR_FLOWER_TwinLanternsFullResolutionDualRayAlpha@LUNAR_FLOWER_TwinLanterns_FullResolutionDualRayAlpha.fx`
- [Masked Edge Smoothing.ini](./presets/XCOM%202/Masked%20Edge%20Smoothing.ini)
  - **Likely purpose.** Masked Edge Smoothing, using 2 enabled techniques.
  - **Enabled effects.** `fine_illusion_shared_mask_orchestrator@fine_illusion_shared_mask_orchestrator.fx`, `fine_illusion_organic_fibonacci_fxaa_smaa@fine_illusion_organic_fibonacci_fxaa_smaa.fx`
- [Ray-Marched Cel Shading and Stylized Ink.ini](./presets/XCOM%202/Ray-Marched%20Cel%20Shading%20and%20Stylized%20Ink.ini)
  - **Likely purpose.** Ray-Marched Cel Shading and Stylized Ink, using 3 enabled techniques.
  - **Enabled effects.** `miXSR_FC_shared_mask_orchestrator@miXSR_FC_shared_mask_orchestrator.fx`, `miXSR_FC_RayM_Cell_Shader@miXSR_FC_RayM_Cell_Shader.fx`, `miXSR_FC_bio_raym_ink_stylized@miXSR_FC_bio_raym_ink_stylized.fx`
- [Rich Tactical Color and Gloss with Clean Edges.ini](./presets/XCOM%202/Rich%20Tactical%20Color%20and%20Gloss%20with%20Clean%20Edges.ini)
  - **Likely purpose.** Rich Tactical Color and Gloss with Clean Edges, using 7 enabled techniques.
  - **Enabled effects.** `fine_illusion_shared_mask_orchestrator@fine_illusion_shared_mask_orchestrator.fx`, `Fine_Cell_fgbAO@Fine_Cell_AO.fx`, `fine_illusion_organic_richness@fine_illusion_organic_richness.fx`, `fine_illusion_ray_tonal_richness@fine_illusion_ray_tonal_richness.fx`, `fine_illusion_rich_colorful_tone@fine_illusion_rich_colorful_tone.fx`, `fine_illusion_obsidian_black_glass_ssr_gloss@fine_illusion_obsidian_black_glass_ssr_gloss.fx`, `fine_illusion_organic_fibonacci_fxaa_smaa@fine_illusion_organic_fibonacci_fxaa_smaa.fx`
- [Shared-Ray Bloom.ini](./presets/XCOM%202/Shared-Ray%20Bloom.ini)
  - **Likely purpose.** Shared-Ray Bloom, using 2 enabled techniques.
  - **Enabled effects.** `RM_00_SharedRayFamilyPlatform@RM_08_SharedRayFamilyPlatform.fx`, `RM_06_BloomFromSharedRecord@RM_06_BloomFromSharedRecord.fx`
- [Stabilized Dual-Ray Lighting with Denoised Detail.ini](./presets/XCOM%202/Stabilized%20Dual-Ray%20Lighting%20with%20Denoised%20Detail.ini)
  - **Likely purpose.** Stabilized Dual-Ray Lighting with Denoised Detail, using 8 enabled techniques.
  - **Enabled effects.** `CAMERA_OBSCURA_StabilizedDetailCaptureV1@CAMERA_OBSCURA_StabilizedDetailCacheV1.fx`, `CAMERA_OBSCURA_StabilizedColorCaptureV1@CAMERA_OBSCURA_StabilizedColorCacheV1.fx`, `CAMERA_OBSCURA_StabilizedLumaCaptureV1@CAMERA_OBSCURA_StabilizedLumaCacheV1.fx`, `LUNAR_FLOWER_TwinLanternsFullResolutionDualRayAlpha@LUNAR_FLOWER_TwinLanterns_FullResolutionDualRayAlpha.fx`, `CAMERA_OBSCURA_ExternalImageDenoiseV1@CAMERA_OBSCURA_ExternalImageDenoiseV1.fx`, `CAMERA_OBSCURA_StabilizedColorReapplyV1@CAMERA_OBSCURA_StabilizedColorCacheV1.fx`, `CAMERA_OBSCURA_StabilizedDetailReapplyV1@CAMERA_OBSCURA_StabilizedDetailCacheV1.fx`, `CAMERA_OBSCURA_StabilizedLumaReapplyV1@CAMERA_OBSCURA_StabilizedLumaCacheV1.fx`
- [Twin Lantern Edge Fill and Detail.ini](./presets/XCOM%202/Twin%20Lantern%20Edge%20Fill%20and%20Detail.ini)
  - **Likely purpose.** Twin Lantern Edge Fill and Detail, using 2 enabled techniques.
  - **Enabled effects.** `CAMERA_OBSCURA_TwinLantern@CAMERA_OBSCURA_TwinLantern.fx`, `LUNAR_FLOWER_TwinLanternsFidelityOverdrive@LUNAR_FLOWER_TwinLanterns_FidelityOverdrive.fx`
