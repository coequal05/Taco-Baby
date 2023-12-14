<?xml version="1.0" encoding="utf-8"?>
<Game configVersion="1">
    
    <Identity Name="41336PublisherName.ExampleGame" Publisher="CN=A4954634-DF4B-47C7-AB70-D3215D246AF1" Version="1.6.0.0"/>
    
    <GameOsVersion>**REPLACE**</GameOsVersion>
    
    <MediaCapture>
        <GameDVRSystemComponent>true</GameDVRSystemComponent>
        <BlockBroadcast>0</BlockBroadcast>
        <BlockGameDVR>0</BlockGameDVR>
    </MediaCapture>
    
    <PersistentLocalStorage>
        <SizeMB>322</SizeMB>
    </PersistentLocalStorage>
    
    <MSAAppId>0000000000000000</MSAAppId>

    <TitleId>FFFFFFFF</TitleId>

    <StoreId>9NZTKMP36L8J</StoreId>
    
    <RelatedProducts>
        <RelatedProduct>9NZTKMP36L8J</RelatedProduct>
        <RelatedProduct>9NQJV5BMKR6C</RelatedProduct>
        <RelatedProduct>9PNX38847DWW</RelatedProduct>
    </RelatedProducts>
    
    <VirtualMachine>
        <XboxAnacondaTitleMemory>Standard</XboxAnacondaTitleMemory>
        <!-- <XboxOneXTitleMemory>Standard</XboxOneXTitleMemory> if MicrosoftGame.config is for Xbox One instead of Xbox Series X&#124;S. -->
    </VirtualMachine>
    
    <MSAFullTrust>false</MSAFullTrust>
    
    <ExecutableList>
         <!-- TargetDeviceFamily="XboxOne" if the MicrosoftGame.config is for Xbox One instead of Xbox Series X&#124;S. -->
        <Executable Name="ExampleGame.exe"
            TargetDeviceFamily="Scarlett"
            Id="Game"
            IsDevOnly="false"
            OverrideDisplayName="Example Game"
            OverrideLogo="OverriddenLogo.png" />
        <Executable Name="ExampleGame_Debug.exe"
            IsDevOnly="true"/>
        <Executable Name="ExampleGame_Profile.exe"
            IsDevOnly="true" />
    </ExecutableList>
    
    <ShellVisuals DefaultDisplayName="Example Game"
        PublisherDisplayName="Example Publisher"
        StoreLogo="StoreLogoFile.png"
        Square150x150Logo="LogoFile150x150.png"
        Square44x44Logo="LogoFile44x44.png"
        Square480x480Logo="LogoFile480x480.png"
        Description="Example Game"
        ForegroundText="light"
        BackgroundColor="#ffffff"
        SplashScreenImage="SplashScreen.png"/>
    
    <Resources>
        <Resource Language="en-us"/>
        <Resource Language="de-de"/>
        <Resource Language="es-mx"/>
    </Resources>

    <DevelopmentOnly>
      <DebugNetworkPortList>
        <DebugNetworkPort>4600</DebugNetworkPort>
      </DebugNetworkPortList>
    </DevelopmentOnly>
</Game>
