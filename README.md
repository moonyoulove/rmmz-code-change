# RPG Maker MZ與MV的代碼差異
## mz新增的class
* ColorFilter
* Video
* FontManager
* EffectManager
* ColorManager
* Scene_Message
* Sprite_Clickable
* Sprite_AnimationMV
* Sprite_Battleback
* Sprite_Gauge
* Sprite_Name
* Window_Scrollable
* Window_StatusBase
* Window_StatusParams
* Window_StatusEquip
* Window_NameBox
***
## mz移除的class
* JsExtensions
* CacheEntry
* CacheMap
* ImageCache
* RequestQueue
* ShaderTilemap
* ToneFilter
* ToneSprite
* Html5Audio
* Decrypter
* ResourceHandler
* Sprite_Base
***
## Array新增的方法
### prototype
* remove
***
## Utils新增的方法
### static
* checkRMVersion
* isLocal
* canUseWebGL
* canUseWebAudioAPI
* canUseCssFontLoading
* canUseIndexedDB
* canPlayOgg
* canPlayWebm
* encodeURI
* escapeHtml
* containsArabic
* setEncryptionInfo
* hasEncryptedImages
* hasEncryptedAudio
* decryptArrayBuffer
***
## Utils移除的方法
### static
* canReadGameFiles
* rgbToCssColor
* generateRuntimeId
* isSupportPassiveEvent
***
## Graphics新增的方法
### static
* setTickHandler
* startGameLoop
* stopGameLoop
* setStage
* showRetryButton
* eraseError
* showScreen
* hideScreen
* resize
* _onTick
* _canRender
* _stretchWidth
* _stretchHeight
* _createLoadingSpinner
* _createFPSCounter
* _clearCanvasFilter
* _switchFPSCounter
* _createPixiApp
* _setupPixi
* _createEffekseerContext
* FPSCounter
* _tickHandler
***
## Graphics移除的方法
### static
* _setupCssFontLoading
* canUseCssFontLoading
* tickStart
* tickEnd
* render
* isWebGL
* hasWebGL
* canUseDifferenceBlend
* canUseSaturationBlend
* setLoadingImage
* updateLoading
* printLoadingError
* eraseLoadingError
* showFps
* hideFps
* loadFont
* isFontLoaded
* playVideo
* _playVideo
* isVideoPlaying
* canPlayVideoType
* setVideoVolume
* callGC
* _testCanvasBlendModes
* _modifyExistingElements
* _createVideo
* _createUpperCanvas
* _updateUpperCanvas
* _clearUpperCanvas
* _paintUpperCanvas
* _createRenderer
* _updateRenderer
* _createFPSMeter
* _createModeBox
* _createGameFontLoader
* _createFontLoader
* _disableTextSelection
* _onVideoLoad
* _onVideoError
* _onVideoEnd
* _updateVisibility
* _isVideoVisible
* _onTouchEnd
* _switchFPSMeter
***
## Bitmap新增的方法
### prototype
* destroy
* strokeRect
* retry
* _ensureCanvas
* _destroyCanvas
* _updateScaleMode
* _startLoading
* _startDecrypting
* _onXhrLoad
***
## Bitmap移除的方法
### static
* request
### prototype
* _clearImgInstance
* _renewCanvas
* touch
* bltImage
* adjustTone
* rotateHue
* blur
* decode
* _setDirty
* checkDirty
* _requestImage
* isRequestOnly
* isRequestReady
* startRequest
***
## Sprite新增的方法
### prototype
* destroy
* hide
* show
* updateVisibility
* setHue
* _onBitmapChange
* _createColorFilter
* _updateColorFilter
***
## Sprite移除的方法
### prototype
* _isInBitmapRect
* _needsTint
* _createTinter
* _executeTint
* _renderCanvas_PIXI
* _renderWebGL_PIXI
* _renderCanvas
* _speedUpCustomBlendModes
* _renderWebGL
***
## Tilemap新增的class
* Layer
* Renderer
***
## Tilemap新增的方法
### prototype
* destroy
* setBitmaps
* _updateBitmaps
* _addAllSpots
* _addSpot
* _addSpotTile
* _addTile
* _addNormalTile
* _addAutotile
* _addTableEdge
* _addShadow
***
## Tilemap移除的方法
### prototype
* refreshTileset
* _updateLayerPositions
* _paintAllTiles
* _paintTiles
* _readLastTiles
* _writeLastTiles
* _drawTile
* _drawNormalTile
* _drawAutotile
* _drawTableEdge
* _drawShadow
***
## TilingSprite新增的方法
### prototype
* destroy
* _onBitmapChange
***
## TilingSprite移除的方法
### prototype
* _renderCanvas_PIXI
* _renderWebGL_PIXI
* _renderCanvas
* _renderWebGL
* updateTransformTS
* _speedUpCustomBlendModes
***
## ScreenSprite新增的方法
### prototype
* destroy
***
## ScreenSprite移除的方法
### static
* warnYep
***
## WindowLayer新增的方法
### prototype
* render
***
## WindowLayer移除的方法
### prototype
* onRemoveAsAChild
* move
* renderCanvas
* _canvasClearWindowRect
* renderWebGL
* _maskWindow
***
## Weather新增的方法
### prototype
* destroy
***
## Stage新增的方法
### prototype
* destroy
***
## WebAudio新增的方法
### static
* _currentTime
* _onUserGesture
* _resetVolume
### prototype
* destroy
* retry
* _startLoading
* _shouldUseDecoder
* _createDecoder
* _destroyDecoder
* _realUrl
* _startXhrLoading
* _startFetching
* _onFetch
* _onError
* _onFetchProcess
* _updateBufferOnFetch
* _concatenateFetchedData
* _updateBuffer
* _readableBuffer
* _decodeAudioData
* _onDecode
* _refreshSourceNode
* _startAllSourceNodes
* _startSourceNode
* _stopSourceNode
* _createPannerNode
* _createGainNode
* _createAllSourceNodes
* _createSourceNode
***
## WebAudio移除的方法
### static
* canPlayOgg
* canPlayM4a
* _detectCodecs
* _onTouchStart
### prototype
* _load
* _createNodes
* _connectNodes
* _readOgg
* _readMp4
* _readLittleEndian
* _readBigEndian
***
## Input新增的方法
### static
* virtualClick
***
## Input移除的方法
### static
* _wrapNwjsAlert
***
## TouchInput新增的方法
### static
* isClicked
* isHovered
* _createNewState
* _onLostFocus
* _onHover
***
## TouchInput移除的方法
### static
* _onPointerDown
***
## DataManager新增的方法
### static
* removeInvalidGlobalInfo
* isGlobalInfoLoaded
* onXhrLoad
* onXhrError
* isMapObject
* extractArrayMetadata
* earliestSavefileId
* emptySavefileId
* savefileInfo
* savefileExists
* makeSavename
* correctDataErrors
***
## DataManager移除的方法
### static
* isThisGameFile
* loadSavefileInfo
* lastAccessedSavefileId
* saveGameWithoutRescue
* loadGameWithoutRescue
***
## ConfigManager新增的方法
### static
* isLoaded
***
## ImageManager新增的方法
### static
* loadBitmapFromUrl
* throwLoadError
***
## ImageManager移除的方法
### static
* _generateCacheKey
* loadEmptyBitmap
* loadNormalBitmap
* reserveAnimation
* reserveBattleback1
* reserveBattleback2
* reserveEnemy
* reserveCharacter
* reserveFace
* reserveParallax
* reservePicture
* reserveSvActor
* reserveSvEnemy
* reserveSystem
* reserveTileset
* reserveTitle1
* reserveTitle2
* reserveBitmap
* reserveNormalBitmap
* releaseReservation
* setDefaultReservationId
* requestAnimation
* requestBattleback1
* requestBattleback2
* requestEnemy
* requestCharacter
* requestFace
* requestParallax
* requestPicture
* requestSvActor
* requestSvEnemy
* requestSystem
* requestTileset
* requestTitle1
* requestTitle2
* requestBitmap
* requestNormalBitmap
* update
* clearRequest
***
## AudioManager新增的方法
### static
* cleanupSe
* throwLoadError
***
## AudioManager移除的方法
### static
* playEncryptedBgm
* createDecryptBuffer
* shouldUseHtml5Audio
* checkWebAudioError
***
## SceneManager新增的方法
### static
* checkBrowser
* initVideo
* setupEventHandlers
* determineRepeatNumber
* onReject
* onUnload
* reloadGame
* showDevTools
* catchNormalError
* catchLoadError
* catchUnknownError
* updateFrameCount
* updateEffekseer
* isGameActive
* onSceneTerminate
* onBeforeSceneStart
***
## SceneManager移除的方法
### static
* _getTimeInMsWithoutMobileSafari
* preferableRendererType
* shouldUseCanvasRenderer
* checkWebGL
* checkFileAccess
* initNwjs
* setupErrorHandlers
* requestUpdate
* tickStart
* tickEnd
* updateManagers
* renderScene
* onSceneLoading
* isCurrentSceneStarted
***
## BattleManager新增的方法
### static
* isTpb
* isActiveTpb
* updatePhase
* updateTpbInput
* checkTpbInputClose
* checkTpbInputOpen
* isPartyTpbInputtable
* needsActorInputCancel
* isTpbMainPhase
* selectNextActor
* selectPreviousActor
* changeCurrentActor
* startActorInput
* finishActorInput
* cancelActorInput
* updateStart
* updateTpb
* updateAllTpbBattlers
* updateTpbBattler
* checkTpbTurnEnd
* endBattlerActions
* endAllBattlersTurn
* displayBattlerStatus
* onEscapeSuccess
* onEscapeFailure
***
## BattleManager移除的方法
### static
* setStatusWindow
* clearActor
* changeActor
* refreshStatus
* isForcedTurn
***
## PluginManager新增的方法
### static
* makeUrl
* throwLoadError
* callCommand
***
## Game_Temp新增的方法
### prototype
* setTouchState
* clearTouchState
* touchTarget
* touchState
* requestBattleRefresh
* clearBattleRefreshRequest
* isBattleRefreshRequested
* retrieveCommonEvent
* requestAnimation
* retrieveAnimation
* requestBalloon
* retrieveBalloon
* lastActionData
* setLastActionData
* setLastUsedSkillId
* setLastUsedItemId
* setLastSubjectActorId
* setLastSubjectEnemyIndex
* setLastTargetActorId
* setLastTargetEnemyIndex
***
## Game_Temp移除的方法
### prototype
* clearCommonEvent
* reservedCommonEvent
***
## Game_System新增的方法
### prototype
* isAutosaveEnabled
* savefileId
* setSavefileId
* mainFontFace
* numberFontFace
* mainFontSize
* windowPadding
***
## Game_Message新增的方法
### prototype
* speakerName
* setSpeakerName
* isRTL
***
## Game_Picture新增的方法
### prototype
* applyEasing
* calcEasing
* easeIn
* easeOut
* easeInOut
***
## Game_Picture移除的方法
### prototype
* erase
***
## Game_Action新增的方法
### prototype
* isForEveryone
* isForAliveFriend
* targetsForEveryone
* randomTargets
* targetsForDead
* targetsForAlive
* targetsForDeadAndAlive
* testLifeAndDeath
* updateLastUsed
* updateLastSubject
* updateLastTarget
***
## Game_BattlerBase新增的方法
### prototype
* paramBasePlus
***
## Game_Battler新增的方法
### prototype
* shouldPopupDamage
* clearTpbChargeTime
* applyTpbPenalty
* initTpbChargeTime
* tpbChargeTime
* startTpbCasting
* startTpbAction
* isTpbCharged
* isTpbReady
* isTpbTimeout
* updateTpb
* updateTpbChargeTime
* updateTpbCastTime
* updateTpbAutoBattle
* updateTpbIdleTime
* tpbAcceleration
* tpbRelativeSpeed
* tpbSpeed
* tpbBaseSpeed
* tpbRequiredCastTime
* onTpbCharged
* shouldDelayTpbCharge
* finishTpbCharge
* isTpbTurnEnd
* initTpbTurn
* startTpbTurn
* makeTpbActions
* onTpbTimeout
* turnCount
* canInput
***
## Game_Battler移除的方法
### prototype
* clearAnimations
* isAnimationRequested
* shiftAnimation
* startAnimation
***
## Game_Actor新增的方法
### prototype
* hide
* skillTypes
* lastSkill
* onEscapeFailure
***
## Game_Actor移除的方法
### prototype
* paramMax
* startAnimation
***
## Game_Unit新增的方法
### prototype
* tpbBaseSpeed
* tpbReferenceTime
* updateTpb
***
## Game_Party新增的方法
### prototype
* removeInvalidMembers
* onEscapeFailure
***
## Game_Troop新增的方法
### prototype
* updatePluralFlags
* isTpbTurnEnd
***
## Game_Map新增的方法
### prototype
* autorunCommonEvents
***
## Game_Player新增的方法
### prototype
* setupForNewGame
***
## Game_Follower新增的方法
### prototype
* isGathered
***
## Game_Followers新增的方法
### prototype
* setup
* data
* reverseData
***
## Game_Followers移除的方法
### prototype
* forEach
* reverseEach
***
## Game_Interpreter新增的方法
### prototype
* loadImages
* picturePoint
* command357
***
## Game_Interpreter移除的方法
### static
* requestImages
***
## Scene_Base新增的方法
### prototype
* isStarted
* isFading
* createColorFilter
* updateColorFilter
* scaleSprite
* centerSprite
* isBottomHelpMode
* isBottomButtonMode
* isRightInputMode
* mainCommandWidth
* buttonAreaTop
* buttonAreaBottom
* buttonAreaHeight
* buttonY
* calcWindowHeight
* requestAutosave
* isAutosaveEnabled
* executeAutosave
* onAutosaveSuccess
* onAutosaveFailure
***
## Scene_Base移除的方法
### prototype
* attachReservation
* detachReservation
* createFadeSprite
***
## Scene_Boot新增的方法
### prototype
* onDatabaseLoaded
* setEncryptionInfo
* loadSystemImages
* loadPlayerData
* loadGameFonts
* isPlayerDataLoaded
* startNormalGame
* resizeScreen
* adjustBoxSize
* adjustWindow
***
## Scene_Boot移除的方法
### static
* loadSystemImages
### prototype
* loadSystemWindowImage
* isGameFontLoaded
***
## Scene_Title新增的方法
### prototype
* adjustBackground
* commandWindowRect
***
## Scene_Title移除的方法
### prototype
* centerSprite
***
## Scene_Map新增的方法
### prototype
* onTransfer
* onTransferEnd
* shouldAutosave
* isPlayerActive
* updateMenuButton
* hideMenuButton
* updateMapNameWindow
* isAnyButtonPressed
* onMapTouch
* mapNameWindowRect
* createButtons
* createMenuButton
***
## Scene_Map移除的方法
### prototype
* createMessageWindow
* createScrollTextWindow
***
## Scene_MenuBase新增的方法
### prototype
* update
* helpAreaTop
* helpAreaBottom
* helpAreaHeight
* mainAreaTop
* mainAreaBottom
* mainAreaHeight
* helpWindowRect
* createButtons
* needsCancelButton
* createCancelButton
* needsPageButtons
* createPageButtons
* updatePageButtons
* arePageButtonsEnabled
***
## Scene_Menu新增的方法
### prototype
* helpAreaHeight
* commandWindowRect
* goldWindowRect
* statusWindowRect
***
## Scene_ItemBase新增的方法
### prototype
* actorWindowRect
* showActorWindow
* hideActorWindow
* isActorWindowActive
***
## Scene_ItemBase移除的方法
### prototype
* showSubWindow
* hideSubWindow
***
## Scene_Item新增的方法
### prototype
* categoryWindowRect
* itemWindowRect
***
## Scene_Skill新增的方法
### prototype
* skillTypeWindowRect
* statusWindowRect
* itemWindowRect
* needsPageButtons
* arePageButtonsEnabled
***
## Scene_Equip新增的方法
### prototype
* statusWindowRect
* commandWindowRect
* slotWindowRect
* itemWindowRect
* statusWidth
* needsPageButtons
* arePageButtonsEnabled
* executeEquipChange
* hideItemWindow
***
## Scene_Status新增的方法
### prototype
* helpAreaHeight
* createProfileWindow
* profileWindowRect
* createStatusWindow
* statusWindowRect
* createStatusParamsWindow
* statusParamsWindowRect
* createStatusEquipWindow
* statusEquipWindowRect
* statusParamsWidth
* statusParamsHeight
* profileHeight
* needsPageButtons
***
## Scene_Options新增的方法
### prototype
* optionsWindowRect
* maxCommands
* maxVisibleCommands
***
## Scene_File新增的方法
### prototype
* helpAreaHeight
* isSavefileEnabled
* helpWindowRect
* listWindowRect
* needsAutosave
* firstSavefileId
***
## Scene_File移除的方法
### prototype
* firstSavefileIndex
***
## Scene_Save新增的方法
### prototype
* firstSavefileId
* executeSave
***
## Scene_Save移除的方法
### prototype
* firstSavefileIndex
***
## Scene_Load新增的方法
### prototype
* firstSavefileId
* executeLoad
***
## Scene_Load移除的方法
### prototype
* firstSavefileIndex
***
## Scene_GameEnd新增的方法
### prototype
* commandWindowRect
***
## Scene_Shop新增的方法
### prototype
* goldWindowRect
* commandWindowRect
* dummyWindowRect
* numberWindowRect
* statusWindowRect
* buyWindowRect
* categoryWindowRect
* sellWindowRect
* statusWidth
***
## Scene_Name新增的方法
### prototype
* editWindowRect
* inputWindowRect
***
## Scene_Debug新增的方法
### prototype
* needsCancelButton
* rangeWindowRect
* editWindowRect
* debugHelpWindowRect
***
## Scene_Battle新增的方法
### prototype
* updateVisibility
* isTimeActive
* shouldAutosave
* updateLogWindowVisibility
* updateStatusWindowVisibility
* shouldOpenStatusWindow
* updateStatusWindowPosition
* statusWindowX
* updateInputWindowVisibility
* needsInputWindowChange
* updateCancelButton
* logWindowRect
* statusWindowRect
* partyCommandWindowRect
* actorCommandWindowRect
* helpWindowRect
* skillWindowRect
* itemWindowRect
* actorWindowRect
* enemyWindowRect
* helpAreaTop
* helpAreaBottom
* helpAreaHeight
* buttonAreaTop
* windowAreaHeight
* createButtons
* createCancelButton
* closeCommandWindows
* hideSubInputWindows
* commandCancel
* startActorSelection
* startEnemySelection
***
## Scene_Battle移除的方法
### prototype
* updateStatusWindow
* updateWindowPositions
* createMessageWindow
* createScrollTextWindow
* refreshStatus
* selectActorSelection
* selectEnemySelection
***
## Scene_Gameover新增的方法
### prototype
* adjustBackground
***
## Sprite_Button新增的方法
### prototype
* setupFrames
* blockWidth
* blockHeight
* loadButtonImage
* buttonData
* checkBitmap
* updateOpacity
* onClick
***
## Sprite_Button移除的方法
### prototype
* callClickHandler
* processTouch
* isActive
* isButtonTouched
* canvasToLocalX
* canvasToLocalY
***
## Sprite_Character新增的方法
### prototype
* checkCharacter
* isObjectCharacter
* isEmptyCharacter
***
## Sprite_Character移除的方法
### prototype
* updateAnimation
* setupAnimation
* setupBalloon
* startBalloon
* updateBalloon
* endBalloon
* isBalloonPlaying
***
## Sprite_Battler新增的方法
### prototype
* checkBattler
* mainSprite
* createDamageSprite
* destroyDamageSprite
* onMouseEnter
* onPress
* onClick
***
## Sprite_Battler移除的方法
### prototype
* updateAnimation
* setupAnimation
***
## Sprite_Actor新增的方法
### prototype
* mainSprite
* shouldStepForward
***
## Sprite_Enemy新增的方法
### prototype
* setHue
***
## Sprite_Animation新增的方法
### prototype
* destroy
* canStart
* shouldWaitForPrevious
* updateEffectGeometry
* processSoundTimings
* processFlashTimings
* checkEnd
* setRotation
* _render
* setProjectionMatrix
* setCameraMatrix
* setViewport
* targetPosition
* targetSpritePosition
* saveViewport
* resetViewport
* onBeforeRender
* onAfterRender
***
## Sprite_Animation移除的方法
### prototype
* remove
* setupRate
* setupDuration
* updateScreenFlash
* absoluteX
* absoluteY
* updateHiding
* loadBitmaps
* isReady
* createSprites
* createCellSprites
* createScreenFlashSprite
* updatePosition
* updateFrame
* currentFrameIndex
* updateAllCellSprites
* updateCellSprite
* processTimingData
* startFlash
* startScreenFlash
* startHiding
***
## Sprite_Damage新增的方法
### prototype
* destroy
* fontFace
* fontSize
* damageColor
* outlineColor
* outlineWidth
* createBitmap
***
## Sprite_Damage移除的方法
### prototype
* digitWidth
* digitHeight
***
## Sprite_StateIcon新增的方法
### prototype
* shouldDisplay
***
## Sprite_Balloon新增的方法
### prototype
* updatePosition
***
## Sprite_Timer新增的方法
### prototype
* destroy
* fontFace
* fontSize
***
## Sprite_Destination新增的方法
### prototype
* destroy
***
## Spriteset_Base新增的方法
### prototype
* destroy
* loadSystemImages
* createBaseFilters
* pictureContainerRect
* createOverallFilters
* updateBaseFilters
* updateOverallFilters
* findTargetSprite
* updateAnimations
* processAnimationRequests
* createAnimation
* createAnimationSprite
* isMVAnimation
* makeTargetSprites
* lastAnimationSprite
* isAnimationForEach
* animationBaseDelay
* animationNextDelay
* animationShouldMirror
* removeAnimation
* removeAllAnimations
* isAnimationPlaying
***
## Spriteset_Base移除的方法
### prototype
* createToneChanger
* createWebGLToneChanger
* createCanvasToneChanger
* createScreenSprites
* updateScreenSprites
* updateToneChanger
* updateWebGLToneChanger
* updateCanvasToneChanger
***
## Spriteset_Map新增的方法
### prototype
* destroy
* loadSystemImages
* updateBalloons
* processBalloonRequests
* createBalloon
* removeBalloon
* removeAllBalloons
* findTargetSprite
* animationBaseDelay
***
## Spriteset_Map移除的方法
### prototype
* _canvasReAddParallax
***
## Spriteset_Battle新增的方法
### prototype
* loadSystemImages
* battleFieldOffsetY
* findTargetSprite
***
## Spriteset_Battle移除的方法
### prototype
* locateBattleback
* battleback1Bitmap
* battleback2Bitmap
* battleback1Name
* battleback2Name
* overworldBattleback1Name
* overworldBattleback2Name
* normalBattleback1Name
* normalBattleback2Name
* terrainBattleback1Name
* terrainBattleback2Name
* defaultBattleback1Name
* defaultBattleback2Name
* shipBattleback1Name
* shipBattleback2Name
* autotileType
* isAnimationPlaying
***
## Window_Base新增的方法
### prototype
* destroy
* checkRectObject
* itemWidth
* itemHeight
* itemPadding
* baseTextRect
* destroyContents
* changeOutlineColor
* drawRect
* textSizeEx
* createTextState
* processAllText
* flushTextState
* createTextBuffer
* processControlCharacter
* processColorChange
* maxFontSizeInLine
* createDimmerSprite
* playCursorSound
* playOkSound
* playBuzzerSound
***
## Window_Base移除的方法
### prototype
* standardFontFace
* standardFontSize
* standardPadding
* textPadding
* standardBackOpacity
* textColor
* normalColor
* crisisColor
* deathColor
* gaugeBackColor
* hpGaugeColor1
* hpGaugeColor2
* mpGaugeColor1
* mpGaugeColor2
* mpCostColor
* powerUpColor
* powerDownColor
* tpGaugeColor1
* tpGaugeColor2
* tpCostColor
* pendingColor
* processNormalCharacter
* processNewPage
* drawGauge
* hpColor
* mpColor
* tpColor
* drawActorCharacter
* drawActorFace
* drawActorName
* drawActorClass
* drawActorNickname
* drawActorLevel
* drawActorIcons
* drawCurrentAndMax
* drawActorHp
* drawActorMp
* drawActorTp
* drawActorSimpleStatus
* paramchangeTextColor
* dimColor1
* dimColor2
* canvasToLocalX
* canvasToLocalY
* reserveFaceImages
***
## Window_Selectable新增的方法
### prototype
* colSpacing
* rowSpacing
* contentsHeight
* overallHeight
* forceSelect
* smoothSelect
* maxVisibleItems
* itemRectWithPadding
* itemLineRect
* isScrollEnabled
* isHoverEnabled
* onTouchSelect
* onTouchOk
* onTouchCancel
* hitIndex
* drawItemBackground
* drawBackgroundRect
* paint
* refreshCursor
* refreshCursorForAll
***
## Window_Selectable移除的方法
### prototype
* spacing
* resetScroll
* bottomRow
* setBottomRow
* itemRectForText
* scrollDown
* scrollUp
* updateArrows
* processWheel
* isTouchedInsideFrame
* onTouch
* isContentsArea
* playOkSound
* playBuzzerSound
* updateCursor
* isCursorVisible
***
## Window_Gold新增的方法
### prototype
* colSpacing
***
## Window_Gold移除的方法
### prototype
* windowWidth
* windowHeight
***
## Window_MenuStatus新增的方法
### prototype
* actor
* drawPendingItemBackground
***
## Window_MenuStatus移除的方法
### prototype
* windowWidth
* windowHeight
* loadImages
* drawItemBackground
***
## Window_ItemCategory新增的方法
### prototype
* needsCommand
* needsSelection
***
## Window_ItemCategory移除的方法
### prototype
* windowWidth
***
## Window_ItemList新增的方法
### prototype
* colSpacing
* itemAt
***
## Window_ItemList移除的方法
### prototype
* spacing
***
## Window_SkillList新增的方法
### prototype
* colSpacing
* itemAt
***
## Window_SkillList移除的方法
### prototype
* spacing
***
## Window_EquipStatus新增的方法
### prototype
* colSpacing
* drawAllParams
* rightArrowWidth
* paramWidth
* paramX
* paramY
***
## Window_EquipStatus移除的方法
### prototype
* windowWidth
* windowHeight
* numVisibleRows
***
## Window_EquipSlot新增的方法
### prototype
* itemAt
* slotNameWidth
***
## Window_EquipSlot移除的方法
### prototype
* slotName
***
## Window_EquipItem新增的方法
### prototype
* maxCols
* colSpacing
* etypeId
***
## Window_Status新增的方法
### prototype
* block1Y
* block2Y
* expTotalValue
* expNextValue
***
## Window_Status移除的方法
### prototype
* drawBlock3
* drawBlock4
* drawHorzLine
* lineColor
* drawParameters
* drawEquipments
* drawProfile
* maxEquipmentLines
***
## Window_Options新增的方法
### prototype
* changeVolume
***
## Window_Options移除的方法
### prototype
* windowWidth
* windowHeight
* updatePlacement
***
## Window_SavefileList新增的方法
### prototype
* numVisibleRows
* indexToSavefileId
* savefileIdToIndex
* isEnabled
* savefileId
* selectSavefile
* drawTitle
***
## Window_SavefileList移除的方法
### prototype
* maxVisibleItems
* drawFileId
* drawGameTitle
***
## Window_ShopCommand新增的方法
### prototype
* setPurchaseOnly
***
## Window_ShopCommand移除的方法
### prototype
* windowWidth
***
## Window_ShopBuy新增的方法
### prototype
* setupGoods
* itemAt
* goodsToItem
* priceWidth
***
## Window_ShopBuy移除的方法
### prototype
* windowWidth
***
## Window_ShopNumber新增的方法
### prototype
* isScrollEnabled
* totalButtonWidth
* buttonSpacing
* drawCurrentItemName
* multiplicationSign
* multiplicationSignX
* drawHorzLine
* itemNameY
* totalPriceY
* itemRect
* isTouchOkEnabled
***
## Window_ShopNumber移除的方法
### prototype
* windowWidth
* updateButtonsVisiblity
* showButtons
* hideButtons
* itemY
* priceY
* isOkTriggered
* updateCursor
***
## Window_NameEdit新增的方法
### prototype
* setup
***
## Window_NameEdit移除的方法
### prototype
* windowWidth
* windowHeight
***
## Window_NameInput新增的方法
### prototype
* setEditWindow
* itemWidth
* groupSpacing
* drawItem
***
## Window_NameInput移除的方法
### prototype
* windowHeight
* refresh
***
## Window_ChoiceList新增的方法
### prototype
* setMessageWindow
* createCancelButton
* update
* updateCancelButton
* placeCancelButton
* windowX
* windowY
* windowHeight
* maxLines
* needsCancelButton
***
## Window_ChoiceList移除的方法
### prototype
* textWidthEx
* contentsHeight
* isOkTriggered
***
## Window_NumberInput新增的方法
### prototype
* setMessageWindow
* itemRect
* isScrollEnabled
* isHoverEnabled
* totalButtonWidth
* buttonSpacing
***
## Window_NumberInput移除的方法
### prototype
* spacing
* updateButtonsVisiblity
* showButtons
* hideButtons
* isOkTriggered
***
## Window_EventItem新增的方法
### prototype
* setMessageWindow
* createCancelButton
* update
* updateCancelButton
* placeCancelButton
* needsNumber
***
## Window_EventItem移除的方法
### prototype
* windowHeight
* numVisibleRows
***
## Window_Message新增的方法
### prototype
* setGoldWindow
* setNameBoxWindow
* setChoiceListWindow
* setNumberInputWindow
* setEventItemWindow
* synchronizeNameBox
* shouldBreakHere
* canBreakHere
* updateSpeakerName
* processControlCharacter
***
## Window_Message移除的方法
### prototype
* subWindows
* createSubWindows
* windowWidth
* windowHeight
* numVisibleRows
***
## Window_ScrollText新增的方法
### prototype
* updatePlacement
***
## Window_BattleLog新增的方法
### prototype
* lineRect
* displayItemMessage
***
## Window_BattleLog移除的方法
### prototype
* windowWidth
* windowHeight
* createBackBitmap
* createBackSprite
* animationBaseDelay
* animationNextDelay
***
## Window_ActorCommand新增的方法
### prototype
* actor
***
## Window_ActorCommand移除的方法
### prototype
* windowWidth
* numVisibleRows
***
## Window_BattleStatus新增的方法
### prototype
* extraHeight
* maxCols
* itemHeight
* rowSpacing
* updatePadding
* actor
* selectActor
* update
* preparePartyRefresh
* performPartyRefresh
* drawItemImage
* drawItemStatus
* faceRect
* nameX
* nameY
* stateIconX
* stateIconY
* basicGaugesX
* basicGaugesY
***
## Window_BattleStatus移除的方法
### prototype
* windowWidth
* windowHeight
* numVisibleRows
* refresh
* basicAreaRect
* gaugeAreaRect
* gaugeAreaWidth
* drawBasicArea
* drawGaugeArea
* drawGaugeAreaWithTp
* drawGaugeAreaWithoutTp
***
## Window_BattleActor新增的方法
### prototype
* processTouch
***
## Window_BattleActor移除的方法
### prototype
* actor
***
## Window_BattleEnemy新增的方法
### prototype
* processTouch
***
## Window_BattleEnemy移除的方法
### prototype
* windowWidth
* windowHeight
* numVisibleRows
***
## Window_DebugRange新增的方法
### prototype
* isSwitchMode
***
## Window_DebugRange移除的方法
### prototype
* windowWidth
* windowHeight
* refresh
***
## Window_DebugEdit新增的方法
### prototype
* deltaForVariable
***
## Window_DebugEdit移除的方法
### prototype
* refresh
