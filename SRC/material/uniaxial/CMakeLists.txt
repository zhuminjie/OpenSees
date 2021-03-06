
target_sources(material
    PRIVATE
      UniaxialMaterial.cpp
      ElasticMaterial.cpp
      Elastic2Material.cpp
      ElasticPowerFunc.cpp
      UVCuniaxial.cpp
      Bilin.cpp
      Bilin02.cpp
      IMKBilin.cpp
      IMKPeakOriented.cpp
      IMKPinching.cpp
      Steel2.cpp
      OriginCentered.cpp
      ConcretewBeta.cpp
      ConcreteD.cpp
      ConcreteSakaiKawashima.cpp
      ConcreteCM.cpp
      SteelMPF.cpp
      c14-SK-M.f
      ElasticMultiLinear.cpp
      ElasticPPMaterial.cpp
      ElasticBilin.cpp
      ParallelMaterial.cpp
      ResilienceLow.cpp
      AxialSp.cpp
      BWBN.cpp
      AxialSpHD.cpp
      AxialSp.cpp
      Neoprene.cpp
      Maxwell.cpp
      ViscousDamper.cpp
      BilinearOilDamper.cpp
      Cast.cpp
      HardeningMaterial.cpp
      HardeningMaterial2.cpp
      Concrete01.cpp
      Concrete02Thermal.cpp
      Steel02Thermal.cpp
      Steel01Thermal.cpp
      Concrete04.cpp
      Concrete06.cpp
      Concrete07.cpp
      ResilienceMaterialHR.cpp
      RambergOsgoodSteel.cpp
      Steel01.cpp
      HystereticMaterial.cpp
      EPPGapMaterial.cpp
      ViscousMaterial.cpp
      SeriesMaterial.cpp
      InitStrainMaterial.cpp
      InitStressMaterial.cpp
      SimpleFractureMaterial.cpp
      MinMaxMaterial.cpp
      TensionOnlyMaterial.cpp
      PathIndependentMaterial.cpp
      CableMaterial.cpp
      ENTMaterial.cpp
      FedeasMaterial.cpp
      DrainMaterial.cpp
      BoucWenOriginal.cpp
      BoucWenMaterial.cpp
      HardeningMaterial2.cpp
      Pinching4Material.cpp
      BarSlipMaterial.cpp
      FatigueMaterial.cpp
      SteelMP.cpp
      SmoothPSConcrete.cpp
      Steel02.cpp
      Steel02Fatigue.cpp
      GNGMaterial.cpp
      Concrete02.cpp
      Concrete02IS.cpp
      Steel03.cpp
      MultiLinear.cpp
      HookGap.cpp
      Bond_SP01.cpp
      UniaxialJ2Plasticity.cpp
      HyperbolicGapMaterial.cpp
      ImpactMaterial.cpp
      ReinforcingSteel.cpp
      ContinuumUniaxial.cpp
      SecantConcrete.cpp
      Concrete01WithSITC.cpp
      ConcretewBeta.cpp
      FRPConfinedConcrete.cpp
      FRPConfinedConcrete02.cpp
      KikuchiAikenHDR.cpp
      KikuchiAikenLRB.cpp
      Concrete05.cpp
      ECC01.cpp
      PrestressedSteelMaterial.cpp
      ElasticBDMaterial.cpp
      ShearPanelMaterial.cpp
      SelfCenteringMaterial.cpp
      BackboneMaterial.cpp
      SAWSMaterial.cpp
      ConfinedConcrete01.cpp
      ModIMKPeakOriented.cpp
      ModIMKPeakOriented02.cpp
      ModIMKPinching.cpp
      ModIMKPinching02.cpp
      pyUCLA.cpp
      Dodd_Restrepo.cpp
      DoddRestrepo.f
      STEELDR.f
      DoddRestr.cpp
      SteelBRB.cpp
      CubicSpline.cpp
      TriMatrix.cpp
      CFSSSWP.cpp
      CFSWSWP.cpp
      Steel4.cpp
      ConcreteECThermal.cpp
      ElasticMaterialThermal.cpp
      StainlessECThermal.cpp
      SteelECThermal.cpp
      DamperMaterial.cpp
      MaterialState.cpp
      OOHystereticMaterial.cpp
      SPSW02.cpp
      TDConcrete.cpp
      TDConcreteEXP.cpp
      TDConcreteMC10.cpp
      TDConcreteMC10NL.cpp
      DegradingPinchedBW.cpp
    PUBLIC
      UniaxialMaterial.h
      ElasticMaterial.h
      Elastic2Material.h
      ElasticPowerFunc.h
      UVCuniaxial.h
      Bilin.h
      Bilin02.h
      IMKBilin.h
      IMKPeakOriented.h
      IMKPinching.h
      Steel2.h
      OriginCentered.h
      ConcretewBeta.h
      ConcreteD.h
      ConcreteSakaiKawashima.h
      ConcreteCM.h
      SteelMPF.h
      ElasticMultiLinear.h
      ElasticPPMaterial.h
      ElasticBilin.h
      ParallelMaterial.h
      ResilienceLow.h
      AxialSp.h
      BWBN.h
      AxialSpHD.h
      AxialSp.h
      Neoprene.h
      Maxwell.h
      ViscousDamper.h
      BilinearOilDamper.h
      Cast.h
      HardeningMaterial.h
      HardeningMaterial2.h
      Concrete01.h
      Concrete02Thermal.h
      Steel02Thermal.h
      Steel01Thermal.h
      Concrete04.h
      Concrete06.h
      Concrete07.h
      ResilienceMaterialHR.h
      RambergOsgoodSteel.h
      Steel01.h
      HystereticMaterial.h
      EPPGapMaterial.h
      ViscousMaterial.h
      SeriesMaterial.h
      InitStrainMaterial.h
      InitStressMaterial.h
      SimpleFractureMaterial.h
      MinMaxMaterial.h
      TensionOnlyMaterial.h
      PathIndependentMaterial.h
      CableMaterial.h
      ENTMaterial.h
      FedeasMaterial.h
      DrainMaterial.h
      BoucWenOriginal.h
      BoucWenMaterial.h
      SecantConcrete.h
      HardeningMaterial2.h
      Pinching4Material.h
      BarSlipMaterial.h
      FatigueMaterial.h
      SteelMP.h
      SmoothPSConcrete.h
      Steel02.h
      Steel02Fatigue.h
      GNGMaterial.h
      Concrete02.h
      Concrete02IS.h
      Steel03.h
      MultiLinear.h
      HookGap.h
      Bond_SP01.h
      UniaxialJ2Plasticity.h
      HyperbolicGapMaterial.h
      ImpactMaterial.h
      ReinforcingSteel.h
      ContinuumUniaxial.h
      Concrete01WithSITC.h
      ConcretewBeta.h
      FRPConfinedConcrete.h
      FRPConfinedConcrete02.h
      KikuchiAikenHDR.h
      KikuchiAikenLRB.h
      Concrete05.h
      ECC01.h
      PrestressedSteelMaterial.h
      ElasticBDMaterial.h
      ShearPanelMaterial.h
      SelfCenteringMaterial.h
      BackboneMaterial.h
      WrapperUniaxialMaterial.h
      SAWSMaterial.h
      ConfinedConcrete01.h
      ModIMKPeakOriented.h
      ModIMKPeakOriented02.h
      ModIMKPinching.h
      ModIMKPinching02.h
      pyUCLA.h
      Dodd_Restrepo.h
      DoddRestr.h
      SteelBRB.h
      CubicSpline.h
      TriMatrix.h
      CFSSSWP.h
      CFSWSWP.h
      Steel4.h
      ConcreteECThermal.h
      ElasticMaterialThermal.h
      StainlessECThermal.h
      SteelECThermal.h
      DamperMaterial.h
      MaterialState.h
      OOHystereticMaterial.h
      SPSW02.h
      TDConcrete.h
      TDConcreteEXP.h
      TDConcreteMC10.h
      TDConcreteMC10NL.h
      DegradingPinchedBW.h
)

target_include_directories(material PUBLIC $(CMAKE_CURRENT_LIST_DIR))

add_subdirectory(PY)
add_subdirectory(snap)
add_subdirectory(backbone)
add_subdirectory(stiffness)
add_subdirectory(strength)
add_subdirectory(unloading)
add_subdirectory(limitState)
