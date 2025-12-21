# Update 32852449

**Build ID**: `21121792`  
**Date**: 2025-12-18 01:52:59 UTC  

## 🔴 Impact Analysis

- **Score**: 70134/100
- **Severity**: CRITICAL
- **Type**: Server (CS2 Dedicated Server depot changed)

### 📦 Changed Depots

| ID | Name |
| :--- | :--- |
| `737` | Binaries Mac |
| `2347771` | CS2 Content (Low Violence) |
| `2347772` | CS2 Content Asia |
| `2347776` | Unknown Depot |
| `733` | Public (Debug) |
| `738` | Binaries Mac ARM |
| `2347774` | CS2 Workshop Linux |
| `2347777` | Unknown Depot |
| `2347779` | CS2 Dedicated Server |
| `730` | Unknown Depot |
| `731` | Public |
| `736` | Binaries Linux |
| `2347770` | CS2 Content |
| `2347773` | CS2 Workshop |
| `228988` | Unknown Depot |
| `2347775` | Unknown Depot |
| `2347778` | Unknown Depot |
| `228990` | Unknown Depot |
| `732` | Public (Beta) |
| `734` | Binaries |
| `735` | Binaries Win64 |

### 🆕 New Strings (1457961)

#### weapons
```
DebugUnlockZoom
?drawPixmap@QPainter@@QEAAXAEBVQRect@@AEBVQPixmap@@0@Z
?drawPixmap@QPainter@@QEAAXAEBVQPoint@@AEBVQPixmap@@@Z
?drawPath@QPainter@@QEAAXAEBVQPainterPath@@@Z
?drawPixmap@QPainter@@QEAAXAEBVQPointF@@AEBVQPixmap@@@Z
?drawPixmap@QPainter@@QEAAXAEBVQRect@@AEBVQPixmap@@@Z
?drawPoints@QPainter@@QEAAXAEBVQPolygonF@@@Z
?drawPixmap@QPainter@@QEAAXAEBVQRectF@@AEBVQPixmap@@0@Z
?drawPixmap@QPainter@@QEAAXHHHHAEBVQPixmap@@@Z
?drawPolygon@QPainter@@QEAAXPEBVQPointF@@HW4FillRule@Qt@@@Z
... and 206 more
```
#### maps
```
m_AssetType = "map_asset"
m_FixType = "VMAP_MANUAL_RECOMPILE"
physics_collision = 
m_IconLg = "game:tools/images/assettypes/physics_lg.png"
m_IconSm = "game:tools/images/assettypes/physics_sm.png"
worldnode_asset = 
resource_remap_table = 
map_asset = 
m_IconLg = "game:tools/images/assettypes/map_lg.png"
m_IconSm = "game:tools/images/assettypes/map_sm.png"
... and 7500 more
```
#### items
```
m_IconLg = "game:tools/images/assettypes/cs2_econ_item_lg.png"
m_IconSm = "game:tools/images/assettypes/cs2_econ_item_sm.png"
m_Name = "cs2_item_editor"
m_Library = "tools/cs2_item_editor.dll"
m_ToolIcon = "game:tools/cs2_item_editor/appicon.png"
  Tasking   :
darkmagenta
magenta
graphcanvas_hover_item_info
graphcanvas_cache_item_pixmap
... and 2162 more
```
#### network
```
?observe@r1@detail@tbb@@YAXAEAVtask_scheduler_observer@d1@23@_N@Z
.?AV?$_Ref_count_obj2@VPinningObserver@oidn@@@std@@
.?AVPinningObserver@oidn@@
.?AVtask_scheduler_observer@d1@detail@tbb@@
Unknown protocol.
PanoramaUIClient001
Source2Client002
Source2ClientUI001
Source2ClientPrediction001
Source2Server001
... and 4707 more
```
#### security
```
m_RequireSearchableIntKey = "model_is_modeldoc"
m_RequireSearchableIntKey = "WorldModelDocAll"
keyvalues_asset = 
  <trustInfo>
  </trustInfo>
AAA Certificate Services0
2http://crl.comodoca.com/AAACertificateServices.crl04
#Sectigo RSA Time Stamping Signer #4
Sectigo RSA Time Stamping CA0
#Sectigo RSA Time Stamping Signer #40
... and 10660 more
```
#### ui
```
m_bShowInRevisionSubMenu = true
1UpdateButtonStatusFromAction()
1OpenMenuForParentsOfAsset()
1OpenMenuForChildrenOfAsset()
ShowContextMenu
CQBindableCommandToolButton
CQBindableCommandPushButton
QLabel
QMenu
QRadioButton
... and 5144 more
```
#### audio
```
sound_asset = 
m_FriendlyName = "Sound"
m_CompilerIdentifier = "CompileSound"
m_Description = "Play Sound"
sound_event_script = 
m_FriendlyName = "Sound Event Script"
m_CompilerIdentifier = "CompileSoundEventScript"
m_RequiredSpecialDependency = "Sound Event Script Version"
sound_stack_script = 
m_FriendlyName = "Sound Stack Script"
... and 1770 more
```
#### other
```
"settings"
"maxres"
"settings"
"settings"
"clampu"
"clampv"
"clampw"
"nocompress"
"settings"
"clampu"
... and 1425732 more
```

### New Protobufs (907)

```protobuf
k_EProtoDebugVisibility_Always
k_EProtoDebugVisibility_Server
k_EProtoDebugVisibility_ValveServer
k_EProtoDebugVisibility_GC
k_EProtoDebugVisibility_Never
CMsgGCStorePurchaseInit
CMsgGCStorePurchaseInitResponse
CMsgSystemBroadcast
CMsgInviteToParty
CMsgInvitationCreated
CMsgPartyInviteResponse
CMsgKickFromParty
CMsgLeaveParty
CMsgServerAvailable
CMsgLANServerAvailable
CMsgDevNewItemRequest
CMsgIncrementKillCountAttribute
CMsgApplySticker
CMsgModifyItemAttribute
CMsgApplyStatTrakSwap
CMsgApplyStrangePart
CMsgApplyPennantUpgrade
CMsgApplyEggEssence
CMsgSortItems
CMsgStoreGetUserData
CMsgStoreGetUserDataResponse
CMsgUpdateItemSchema
CMsgGCError
CMsgRequestInventoryRefresh
CMsgConVarValue
CMsgReplicateConVars
CMsgUseItem
CMsgReplayUploadedToYouTube
CMsgConsumableExhausted
CMsgItemAcknowledged__DEPRECATED
CMsgSetItemPositions
CMsgGCReportAbuse
CMsgGCReportAbuseResponse
CMsgGCNameItemNotification
CMsgGCClientDisplayNotification
CClientDisplayNotification
CMsgGCShowItemsPickedUp
CMsgGCIncrementKillCountResponse
CMsgGCItemPreviewItemBoughtNotification
CMsgGCStorePurchaseCancel
CMsgGCStorePurchaseCancelResponse
CMsgGCStorePurchaseFinalize
CMsgGCStorePurchaseFinalizeResponse
CMsgGCBannedWordListRequest
CMsgGCRequestAnnouncements
CMsgGCRequestAnnouncementsResponse
CMsgGCBannedWord
CMsgGCBannedWordListResponse
CMsgGCToGCBannedWordListBroadcast
CMsgGCToGCBannedWordListUpdated
CMsgGCToGCDirtySDOCache
CMsgGCToGCDirtyMultipleSDOCache
CMsgGCCollectItem
CMsgSDONoMemcached
CMsgGCToGCUpdateSQLKeyValue
CMsgGCToGCIsTrustedServer
CMsgGCToGCIsTrustedServerResponse
CMsgGCToGCBroadcastConsoleCommand
CMsgGCServerVersionUpdated
CServerVersionUpdated
CMsgGCClientVersionUpdated
CClientVersionUpdated
CMsgGCToGCWebAPIAccountChanged
CMsgGCToGCRequestPassportItemGrant
CMsgGameServerInfo
CMsgAdjustEquipSlot
CMsgAdjustEquipSlots
CMsgOpenCrate
CMsgAcknowledgeRentalExpiration
k_EMsgGCSystemMessage
k_EMsgGCReplicateConVars
k_EMsgGCConVarUpdated
k_EMsgGCInQueue
k_EMsgGCInviteToParty
k_EMsgGCInvitationCreated
k_EMsgGCPartyInviteResponse
k_EMsgGCKickFromParty
k_EMsgGCLeaveParty
CServerAvailable
k_EMsgGCServerAvailable
CClientConnectToServer
k_EMsgGCClientConnectToServer
k_EMsgGCGameServerInfo
k_EMsgGCError
k_EMsgGCReplay_UploadedToYouTube
k_EMsgGCLANServerAvailable
k_EProtoObjectPartyInvite
k_EProtoObjectLobbyInvite
CMsgCsgoSteamUserStatChange
CMsgGC_ServerQuestUpdateData
CMsgGCCStrike15_v2_MatchmakingGC2ServerConfirm
CMsgGCCStrike15_v2_GC2ServerReservationUpdate
CMsgGCCStrike15_v2_MatchmakingStart
CMsgGCCStrike15_v2_MatchmakingStop
CMsgGCCStrike15_v2_MatchmakingGC2ClientUpdate_Note
CMsgGCCStrike15_v2_MatchmakingClient2ServerPing
CMsgGCCStrike15_v2_MatchmakingGC2ClientUpdate
CMsgGCCStrike15_v2_MatchmakingGC2ServerReserve
CMsgGCCStrike15_v2_MatchmakingServerReservationResponse
CMsgGCCStrike15_v2_MatchmakingGC2ClientReserve
CMsgGCCStrike15_v2_MatchmakingServerRoundStats
CMsgGCCStrike15_v2_MatchmakingClient2GCHello
CMsgGCCStrike15_v2_MatchmakingGC2ClientHello
CMsgGCCStrike15_v2_AccountPrivacySettings
CMsgGCCStrike15_v2_MatchmakingGC2ClientAbandon
CMsgGCCStrike15_v2_ClientGCRankUpdate
CMsgGCCStrike15_v2_MatchmakingOperator2GCBlogUpdate
CMsgGCCStrike15_v2_ServerNotificationForUserPenalty
CMsgGCCStrike15_v2_ClientReportPlayer
CMsgGCCStrike15_v2_ClientCommendPlayer
CMsgGCCStrike15_v2_ClientReportServer
CMsgGCCStrike15_v2_ClientReportResponse
CMsgGCCStrike15_v2_ClientRequestWatchInfoFriends
CMsgGCCStrike15_v2_ClientRequestJoinFriendData
CMsgGCCStrike15_v2_ClientRequestJoinServerData
CMsgGCCstrike15_v2_ClientRedeemMissionReward
CMsgGCCstrike15_v2_ClientRedeemFreeReward
CMsgGCCstrike15_v2_GC2ServerNotifyXPRewarded
CMsgGCCStrike15_v2_ClientNetworkConfig
CMsgGCCStrike15_ClientDeepStats
CMsgGCCStrike15_v2_WatchInfoUsers
CMsgGCCStrike15_v2_ClientRequestPlayersProfile
CMsgGCCStrike15_v2_PlayersProfile
CMsgGCCStrike15_v2_PremierSeasonSummary
CMsgGCCStrike15_v2_PlayerOverwatchCaseUpdate
CMsgGCCStrike15_v2_PlayerOverwatchCaseAssignment
CMsgGCCStrike15_v2_PlayerOverwatchCaseStatus
CClientHeaderOverwatchEvidence
CMsgGCCStrike15_v2_GC2ClientTextMsg
CMsgGCCStrike15_v2_Client2GCTextMsg
CMsgGCCStrike15_v2_MatchEndRunRewardDrops
CMsgGCCStrike15_v2_MatchEndRewardDropsNotification
CMsgItemAcknowledged
CMsgGCCStrike15_v2_Client2GCEconPreviewDataBlockRequest
CMsgGCCStrike15_v2_Client2GCEconPreviewDataBlockResponse
CMsgGCCStrike15_v2_MatchListRequestCurrentLiveGames
CMsgGCCStrike15_v2_MatchListRequestLiveGameForUser
CMsgGCCStrike15_v2_MatchListRequestRecentUserGames
CMsgGCCStrike15_v2_MatchListRequestTournamentGames
CMsgGCCStrike15_v2_MatchListRequestFullGameInfo
CMsgGCCStrike15_v2_MatchList
CMsgGCCStrike15_v2_MatchListTournamentOperatorMgmt
CMsgGCCStrike15_v2_Predictions
CMsgGCCStrike15_v2_Fantasy
CMsgLegacySource1ClientWelcome
CMsgSOCacheSubscribed
CMsgSOCacheSubscriptionCheck
CMsgCStrike15Welcome
CMsgGCCStrike15_v2_ClientVarValueNotificationInfo
CMsgGCCStrike15_v2_ServerVarValueNotificationInfo
CMsgGCCStrike15_v2_GiftsLeaderboardRequest
CMsgGCCStrike15_v2_GiftsLeaderboardResponse
CMsgGCCStrike15_v2_ClientSubmitSurveyVote
CMsgGCCStrike15_v2_Server2GCClientValidate
CClientValidate
CMsgGCCStrike15_v2_GC2ClientTournamentInfo
CMsgGCCStrike15_v2_GC2ClientNotifyXPShop
CMsgGCCStrike15_v2_Client2GcAckXPShopTracks
CMsgGCCStrike15_v2_MatchmakingGC2ClientSearchStats
CMsgGC_GlobalGame_Subscribe
CMsgGC_GlobalGame_Unsubscribe
CMsgGC_GlobalGame_Play
CMsgGCCStrike15_v2_AcknowledgePenalty
CMsgGCCStrike15_v2_Client2GCRequestPrestigeCoin
CMsgGCCStrike15_v2_Client2GCStreamUnlock
CMsgGCCStrike15_v2_ClientToGCRequestElevate
CMsgGCCStrike15_v2_ClientToGCChat
CMsgGCCStrike15_v2_GCToClientChat
CMsgGCCStrike15_v2_ClientAuthKeyCode
CMsgGCCStrike15_GotvSyncPacket
CMsgGCCStrike15_v2_ClientPlayerDecalSign
CMsgGCCStrike15_v2_BetaEnrollment
CMsgGCCStrike15_v2_ClientLogonFatalError
CMsgGCCStrike15_v2_ClientPollState
CMsgGCCStrike15_v2_Party_Register
CMsgGCCStrike15_v2_Party_Search
CMsgGCCStrike15_v2_Party_SearchResults
CMsgGCCStrike15_v2_Party_Invite
CMsgGCCStrike15_v2_Account_RequestCoPlays
CMsgGCCStrike15_v2_ClientToGCRequestTicket
CMsgGCToClientSteamDatagramTicket
CMsgGCCStrike15_v2_ClientRequestOffers
CMsgGCCStrike15_v2_ClientRequestSouvenir
CMsgGCCStrike15_v2_ClientAccountBalance
CMsgGCCStrike15_v2_ClientPartyJoinRelay
CMsgGCCStrike15_v2_ClientPartyWarning
CMsgGCCStrike15_v2_SetEventFavorite
CMsgGCCStrike15_v2_GetEventFavorites_Request
CMsgGCCStrike15_v2_GetEventFavorites_Response
CMsgGCCStrike15_v2_ClientPerfReport
CMsgGCCStrike15_v2_ClientReportValidation
CMsgGCCStrike15_v2_GC2ClientRefuseSecureMode
CMsgGCCStrike15_v2_GC2ClientRequestValidation
CMsgGCCStrike15_v2_GC2ClientInitSystem
CMsgGCCStrike15_v2_GC2ClientInitSystem_Response
CMsgGCCStrike15_v2_SetPlayerLeaderboardSafeName
CMsgRequestRecurringMissionSchedule
CMsgRecurringMissionSchema
k_EMsgGCCStrike15_v2_Base
k_EMsgGCCStrike15_v2_MatchmakingStart
k_EMsgGCCStrike15_v2_MatchmakingStop
k_EMsgGCCStrike15_v2_MatchmakingClient2ServerPing
k_EMsgGCCStrike15_v2_MatchmakingGC2ClientUpdate
k_EMsgGCCStrike15_v2_MatchmakingServerReservationResponse
k_EMsgGCCStrike15_v2_MatchmakingGC2ClientReserve
k_EMsgGCCStrike15_v2_MatchmakingClient2GCHello
k_EMsgGCCStrike15_v2_MatchmakingGC2ClientHello
k_EMsgGCCStrike15_v2_MatchmakingGC2ClientAbandon
k_EMsgGCCStrike15_v2_MatchmakingOperator2GCBlogUpdate
k_EMsgGCCStrike15_v2_ServerNotificationForUserPenalty
k_EMsgGCCStrike15_v2_ClientReportPlayer
k_EMsgGCCStrike15_v2_ClientReportServer
k_EMsgGCCStrike15_v2_ClientCommendPlayer
k_EMsgGCCStrike15_v2_ClientReportResponse
k_EMsgGCCStrike15_v2_ClientCommendPlayerQuery
k_EMsgGCCStrike15_v2_ClientCommendPlayerQueryResponse
k_EMsgGCCStrike15_v2_WatchInfoUsers
k_EMsgGCCStrike15_v2_ClientRequestPlayersProfile
k_EMsgGCCStrike15_v2_PlayersProfile
k_EMsgGCCStrike15_v2_PlayerOverwatchCaseUpdate
k_EMsgGCCStrike15_v2_PlayerOverwatchCaseAssignment
k_EMsgGCCStrike15_v2_PlayerOverwatchCaseStatus
k_EMsgGCCStrike15_v2_GC2ClientTextMsg
k_EMsgGCCStrike15_v2_Client2GCTextMsg
k_EMsgGCCStrike15_v2_MatchEndRunRewardDrops
k_EMsgGCCStrike15_v2_MatchEndRewardDropsNotification
k_EMsgGCCStrike15_v2_ClientRequestWatchInfoFriends2
k_EMsgGCCStrike15_v2_MatchList
k_EMsgGCCStrike15_v2_MatchListRequestCurrentLiveGames
k_EMsgGCCStrike15_v2_MatchListRequestRecentUserGames
k_EMsgGCCStrike15_v2_GC2ServerReservationUpdate
k_EMsgGCCStrike15_v2_ClientVarValueNotificationInfo
k_EMsgGCCStrike15_v2_MatchListRequestTournamentGames
k_EMsgGCCStrike15_v2_MatchListRequestFullGameInfo
k_EMsgGCCStrike15_v2_GiftsLeaderboardRequest
k_EMsgGCCStrike15_v2_GiftsLeaderboardResponse
k_EMsgGCCStrike15_v2_ServerVarValueNotificationInfo
k_EMsgGCCStrike15_v2_ClientSubmitSurveyVote
k_EMsgGCCStrike15_v2_Server2GCClientValidate
k_EMsgGCCStrike15_v2_MatchListRequestLiveGameForUser
k_EMsgGCCStrike15_v2_Client2GCEconPreviewDataBlockRequest
k_EMsgGCCStrike15_v2_Client2GCEconPreviewDataBlockResponse
k_EMsgGCCStrike15_v2_AccountPrivacySettings
k_EMsgGCCStrike15_v2_SetMyActivityInfo
k_EMsgGCCStrike15_v2_MatchListRequestTournamentPredictions
k_EMsgGCCStrike15_v2_MatchListUploadTournamentPredictions
k_EMsgGCCStrike15_v2_DraftSummary
k_EMsgGCCStrike15_v2_ClientRequestJoinFriendData
k_EMsgGCCStrike15_v2_ClientRequestJoinServerData
k_EMsgGCCStrike15_v2_GC2ClientTournamentInfo
k_EMsgGC_GlobalGame_Subscribe
k_EMsgGC_GlobalGame_Unsubscribe
k_EMsgGC_GlobalGame_Play
k_EMsgGCCStrike15_v2_AcknowledgePenalty
k_EMsgGCCStrike15_v2_Client2GCRequestPrestigeCoin
k_EMsgGCCStrike15_v2_GC2ClientGlobalStats
k_EMsgGCCStrike15_v2_Client2GCStreamUnlock
k_EMsgGCCStrike15_v2_FantasyRequestClientData
k_EMsgGCCStrike15_v2_FantasyUpdateClientData
k_EMsgGCCStrike15_v2_GCToClientSteamdatagramTicket
k_EMsgGCCStrike15_v2_ClientToGCRequestTicket
k_EMsgGCCStrike15_v2_ClientToGCRequestElevate
k_EMsgGCCStrike15_v2_GlobalChat
k_EMsgGCCStrike15_v2_GlobalChat_Subscribe
k_EMsgGCCStrike15_v2_GlobalChat_Unsubscribe
k_EMsgGCCStrike15_v2_ClientAuthKeyCode
k_EMsgGCCStrike15_v2_GotvSyncPacket
k_EMsgGCCStrike15_v2_ClientPlayerDecalSign
k_EMsgGCCStrike15_v2_ClientLogonFatalError
k_EMsgGCCStrike15_v2_ClientPollState
k_EMsgGCCStrike15_v2_Party_Register
k_EMsgGCCStrike15_v2_Party_Unregister
k_EMsgGCCStrike15_v2_Party_Search
k_EMsgGCCStrike15_v2_Party_Invite
k_EMsgGCCStrike15_v2_Account_RequestCoPlays
k_EMsgGCCStrike15_v2_ClientGCRankUpdate
k_EMsgGCCStrike15_v2_ClientRequestOffers
k_EMsgGCCStrike15_v2_ClientAccountBalance
k_EMsgGCCStrike15_v2_ClientPartyJoinRelay
k_EMsgGCCStrike15_v2_ClientPartyWarning
k_EMsgGCCStrike15_v2_SetEventFavorite
k_EMsgGCCStrike15_v2_GetEventFavorites_Request
k_EMsgGCCStrike15_v2_ClientPerfReport
k_EMsgGCCStrike15_v2_GetEventFavorites_Response
k_EMsgGCCStrike15_v2_ClientRequestSouvenir
k_EMsgGCCStrike15_v2_ClientReportValidation
k_EMsgGCCStrike15_v2_GC2ClientRefuseSecureMode
k_EMsgGCCStrike15_v2_GC2ClientRequestValidation
k_EMsgGCCStrike15_v2_ClientRedeemMissionReward
k_EMsgGCCStrike15_ClientDeepStats
k_EMsgGCCStrike15_StartAgreementSessionInGame
k_EMsgGCCStrike15_v2_GC2ClientInitSystem
k_EMsgGCCStrike15_v2_GC2ClientInitSystem_Response
k_EMsgGCCStrike15_v2_PrivateQueues
k_EMsgGCCStrike15_v2_MatchListTournamentOperatorMgmt
k_EMsgGCCStrike15_v2_BetaEnrollment
k_EMsgGCCStrike15_v2_SetPlayerLeaderboardSafeName
k_EMsgGCCStrike15_v2_ClientRedeemFreeReward
k_EMsgGCCStrike15_v2_ClientNetworkConfig
k_EMsgGCCStrike15_v2_GC2ClientNotifyXPShop
k_EMsgGCCStrike15_v2_Client2GcAckXPShopTracks
k_EMsgGCCStrike15_v2_MatchmakingGC2ClientSearchStats
k_EMsgGCCStrike15_v2_PremierSeasonSummary
k_EMsgGCCStrike15_v2_RequestRecurringMissionSchedule
k_EMsgGCCStrike15_v2_RecurringMissionSchema
k_EMsgGCCStrike15_v2_VolatileItemClaimReward
k_ECsgoSteamUserStat_XpEarnedGames
k_ECsgoSteamUserStat_MatchWinsCompetitive
k_ECsgoSteamUserStat_SurvivedDangerZone
k_EQuestType_Operation
k_EQuestType_RecurringMission
k_EClientReportingVersion_OldVersion
k_EClientReportingVersion_BetaVersion
k_EClientReportingVersion_SupportsTrustedMode
k_EInitSystemResult_Invalid
k_EInitSystemResult_Success
k_EInitSystemResult_None
k_EInitSystemResult_NotFound
k_EInitSystemResult_Existing
k_EInitSystemResult_FailedOpen
k_EInitSystemResult_Mismatch
k_EInitSystemResult_FailedInit
k_EInitSystemResult_Max
CMsgGCGiftedItems
CMsgGCDev_SchemaReservationRequest
CMsgCasketItem
CMsgGCUserTrackTimePlayedConsecutively
CUserTrackTimePlayedConsecutively
CMsgGCItemCustomizationNotification
k_EMsgGCBase
k_EMsgGCSetItemPosition
k_EMsgGCCraft
k_EMsgGCCraftResponse
k_EMsgGCDelete
k_EMsgGCVerifyCacheSubscription
k_EMsgGCNameItem
k_EMsgGCUnlockCrate_DEPRECATED
k_EMsgGCUnlockCrateResponse
k_EMsgGCPaintItem
k_EMsgGCPaintItemResponse
k_EMsgGCGoldenWrenchBroadcast
k_EMsgGCMOTDRequest
k_EMsgGCMOTDRequestResponse
k_EMsgGCAddItemToSocket_DEPRECATED
k_EMsgGCAddItemToSocketResponse_DEPRECATED
k_EMsgGCAddSocketToBaseItem_DEPRECATED
k_EMsgGCAddSocketToItem_DEPRECATED
k_EMsgGCAddSocketToItemResponse_DEPRECATED
k_EMsgGCNameBaseItem
k_EMsgGCNameBaseItemResponse
k_EMsgGCRemoveSocketItem_DEPRECATED
k_EMsgGCRemoveSocketItemResponse_DEPRECATED
k_EMsgGCCustomizeItemTexture
k_EMsgGCCustomizeItemTextureResponse
k_EMsgGCUseItemRequest
k_EMsgGCUseItemResponse
k_EMsgGCGiftedItems_DEPRECATED
k_EMsgGCRemoveItemName
k_EMsgGCRemoveItemPaint
k_EMsgGCGiftWrapItem
k_EMsgGCGiftWrapItemResponse
k_EMsgGCDeliverGift
k_EMsgGCDeliverGiftResponseGiver
k_EMsgGCDeliverGiftResponseReceiver
k_EMsgGCUnwrapGiftRequest
k_EMsgGCUnwrapGiftResponse
k_EMsgGCSetItemStyle
k_EMsgGCUsedClaimCodeItem
k_EMsgGCSortItems
k_EMsgGC_RevolvingLootList_DEPRECATED
k_EMsgGCLookupAccount
k_EMsgGCLookupAccountResponse
k_EMsgGCLookupAccountName
k_EMsgGCLookupAccountNameResponse
k_EMsgGCUpdateItemSchema
k_EMsgGCRemoveCustomTexture
k_EMsgGCRemoveCustomTextureResponse
k_EMsgGCRemoveMakersMark
k_EMsgGCRemoveMakersMarkResponse
k_EMsgGCRemoveUniqueCraftIndex
k_EMsgGCRemoveUniqueCraftIndexResponse
k_EMsgGCSaxxyBroadcast
k_EMsgGCBackpackSortFinished
k_EMsgGCCollectItem
k_EMsgGCItemAcknowledged__DEPRECATED
k_EMsgGC_ReportAbuse
k_EMsgGC_ReportAbuseResponse
k_EMsgGCNameItemNotification
k_EMsgGCApplyConsumableEffects
k_EMsgGCConsumableExhausted
k_EMsgGCShowItemsPickedUp
k_EMsgGCClientDisplayNotification
k_EMsgGCApplyStrangePart
k_EMsgGC_IncrementKillCountAttribute
k_EMsgGC_IncrementKillCountResponse
k_EMsgGCApplyPennantUpgrade
k_EMsgGCSetItemPositions
k_EMsgGCApplyEggEssence
k_EMsgGCNameEggEssenceResponse
k_EMsgGCPaintKitItem
k_EMsgGCPaintKitBaseItem
k_EMsgGCPaintKitItemResponse
k_EMsgGCGiftedItems
k_EMsgGCUnlockItemStyle
k_EMsgGCUnlockItemStyleResponse
k_EMsgGCApplySticker
k_EMsgGCItemAcknowledged
k_EMsgGCStatTrakSwap
k_EMsgGCUserTrackTimePlayedConsecutively
k_EMsgGCItemCustomizationNotification
k_EMsgGCModifyItemAttribute
k_EMsgGCCasketItemAdd
k_EMsgGCCasketItemExtract
k_EMsgGCCasketItemLoadContents
k_EMsgGCTradingBase
k_EMsgGCTrading_InitiateTradeRequest
k_EMsgGCTrading_InitiateTradeResponse
k_EMsgGCTrading_StartSession
k_EMsgGCTrading_SetItem
k_EMsgGCTrading_RemoveItem
k_EMsgGCTrading_UpdateTradeInfo
k_EMsgGCTrading_SetReadiness
k_EMsgGCTrading_ReadinessResponse
k_EMsgGCTrading_SessionClosed
k_EMsgGCTrading_CancelSession
k_EMsgGCTrading_TradeChatMsg
k_EMsgGCTrading_ConfirmOffer
k_EMsgGCTrading_TradeTypingChatMsg
CServerBrowser_FavoriteServer
k_EMsgGCServerBrowser_FavoriteServer
CServerBrowser_BlacklistServer
k_EMsgGCServerBrowser_BlacklistServer
CServerRentalsBase
k_EMsgGCServerRentalsBase
k_EMsgGCItemPreviewCheckStatus
k_EMsgGCItemPreviewStatusResponse
k_EMsgGCItemPreviewRequest
k_EMsgGCItemPreviewRequestResponse
k_EMsgGCItemPreviewExpire
k_EMsgGCItemPreviewExpireNotification
k_EMsgGCItemPreviewItemBoughtNotification
k_EMsgGCDev_NewItemRequest
k_EMsgGCDev_NewItemRequestResponse
k_EMsgGCDev_PaintKitDropItem
k_EMsgGCDev_SchemaReservationRequest
k_EMsgGCStoreGetUserData
k_EMsgGCStoreGetUserDataResponse
k_EMsgGCStorePurchaseInit_DEPRECATED
k_EMsgGCStorePurchaseInitResponse_DEPRECATED
k_EMsgGCStorePurchaseFinalize
k_EMsgGCStorePurchaseFinalizeResponse
k_EMsgGCStorePurchaseCancel
k_EMsgGCStorePurchaseCancelResponse
k_EMsgGCStorePurchaseQueryTxn
k_EMsgGCStorePurchaseQueryTxnResponse
k_EMsgGCStorePurchaseInit
k_EMsgGCStorePurchaseInitResponse
k_EMsgGCBannedWordListRequest
k_EMsgGCBannedWordListResponse
k_EMsgGCToGCBannedWordListBroadcast
k_EMsgGCToGCBannedWordListUpdated
k_EMsgGCToGCDirtySDOCache
k_EMsgGCToGCDirtyMultipleSDOCache
k_EMsgGCToGCUpdateSQLKeyValue
k_EMsgGCToGCIsTrustedServer
k_EMsgGCToGCIsTrustedServerResponse
k_EMsgGCToGCBroadcastConsoleCommand
k_EMsgGCServerVersionUpdated
k_EMsgGCToGCWebAPIAccountChanged
k_EMsgGCRequestAnnouncements
k_EMsgGCRequestAnnouncementsResponse
k_EMsgGCRequestPassportItemGrant
k_EMsgGCClientVersionUpdated
k_EMsgGCRecurringSubscriptionStatus
k_EMsgGCAdjustEquipSlotsManual
k_EMsgGCAdjustEquipSlotsShuffle
k_EMsgGCOpenCrate
k_EMsgGCAcknowledgeRentalExpiration
k_EMsgGCVolatileItemLoadContents
CMsgResponse
CMsgResponseOK
k_EGCMsgResponseOK
CMsgResponseDenied
k_EGCMsgResponseDenied
CMsgResponseServerError
k_EGCMsgResponseServerError
CMsgResponseTimeout
k_EGCMsgResponseTimeout
CMsgResponseInvalid
k_EGCMsgResponseInvalid
CMsgResponseNoMatch
k_EGCMsgResponseNoMatch
CMsgResponseUnknownError
k_EGCMsgResponseUnknownError
CMsgResponseNotLoggedOn
k_EGCMsgResponseNotLoggedOn
CMsgFailedToCreate
k_EGCMsgFailedToCreate
CMsgLimitExceeded
k_EGCMsgLimitExceeded
CMsgCommitUnfinalized
k_EGCMsgCommitUnfinalized
k_EGCItemCustomizationNotification_NameItem
k_EGCItemCustomizationNotification_UnlockCrate
k_EGCItemCustomizationNotification_XRayItemReveal
k_EGCItemCustomizationNotification_XRayItemClaim
k_EGCItemCustomizationNotification_CasketTooFull
k_EGCItemCustomizationNotification_CasketContents
k_EGCItemCustomizationNotification_CasketAdded
k_EGCItemCustomizationNotification_CasketRemoved
k_EGCItemCustomizationNotification_CasketInvFull
k_EGCItemCustomizationNotification_NameBaseItem
k_EGCItemCustomizationNotification_RemoveItemName
k_EGCItemCustomizationNotification_RemoveSticker
k_EGCItemCustomizationNotification_ExtractSticker
k_EGCItemCustomizationNotification_EncapsulateSticker
k_EGCItemCustomizationNotification_ApplySticker
k_EGCItemCustomizationNotification_StatTrakSwap
k_EGCItemCustomizationNotification_RemovePatch
k_EGCItemCustomizationNotification_ApplyPatch
k_EGCItemCustomizationNotification_ApplyKeychain
k_EGCItemCustomizationNotification_RemoveKeychain
k_EGCItemCustomizationNotification_ActivateFanToken
k_EGCItemCustomizationNotification_ActivateOperationCoin
k_EGCItemCustomizationNotification_GraffitiUnseal
k_EGCItemCustomizationNotification_GenerateSouvenir
k_EGCItemCustomizationNotification_ClientRedeemMissionReward
k_EGCItemCustomizationNotification_ClientRedeemFreeReward
k_EGCItemCustomizationNotification_XpShopUseTicket
k_EGCItemCustomizationNotification_XpShopAckTracks
CMsgSOIDOwner
CMsgSOSingleObject
CMsgSOMultipleObjects
CMsgSOCacheUnsubscribed
CMsgSOCacheSubscriptionRefresh
CMsgSOCacheVersion
CMsgAccountDetails
CMsgGCMultiplexMessage
CMsgGCMultiplexMessage_Response
CMsgMasterAck
CMsgMasterAck_Response
CMsgMasterStartupComplete
CMsgRouted
CMsgRoutedReply
CMsgGCUpdateSessionIP
CMsgGCRequestSessionIP
CMsgGCRequestSessionIPResponse
CMsgSOCacheHaveVersion
CMsgClientHello
CMsgServerHello
CMsgClientWelcome
CMsgConnectionStatus
CMsgSerializedSOCache
CClientLauncherType
CClientLauncherType_DEFAULT
CClientLauncherType_PERFECTWORLD
CClientLauncherType_STEAMCHINA
CClientLauncherType_SOURCE2
CMsgGCHVacVerificationChange
CMsgGCHAccountPhoneNumberChange
CMsgGCHInviteUserToLobby
CMsgGCHRecurringSubscriptionStatusChange
CMsgInvalid
k_EGCMsgInvalid
CMsgMulti
k_EGCMsgMulti
CMsgGenericReply
k_EGCMsgGenericReply
CMsgSystemBase
k_EGCMsgSystemBase
CMsgAchievementAwarded
k_EGCMsgAchievementAwarded
CMsgConCommand
k_EGCMsgConCommand
CMsgStartPlaying
k_EGCMsgStartPlaying
CMsgStopPlaying
k_EGCMsgStopPlaying
CMsgStartGameserver
k_EGCMsgStartGameserver
CMsgStopGameserver
k_EGCMsgStopGameserver
CMsgWGRequest
k_EGCMsgWGRequest
CMsgWGResponse
k_EGCMsgWGResponse
CMsgGetUserGameStatsSchema
k_EGCMsgGetUserGameStatsSchema
CMsgGetUserGameStatsSchemaResponse
k_EGCMsgGetUserGameStatsSchemaResponse
CMsgGetUserStatsDEPRECATED
k_EGCMsgGetUserStatsDEPRECATED
CMsgGetUserStatsResponse
k_EGCMsgGetUserStatsResponse
CMsgAppInfoUpdated
k_EGCMsgAppInfoUpdated
CMsgValidateSession
k_EGCMsgValidateSession
CMsgValidateSessionResponse
k_EGCMsgValidateSessionResponse
CMsgLookupAccountFromInput
k_EGCMsgLookupAccountFromInput
CMsgSendHTTPRequest
k_EGCMsgSendHTTPRequest
CMsgSendHTTPRequestResponse
k_EGCMsgSendHTTPRequestResponse
CMsgPreTestSetup
k_EGCMsgPreTestSetup
CMsgRecordSupportAction
k_EGCMsgRecordSupportAction
CMsgGetAccountDetails_DEPRECATED
k_EGCMsgGetAccountDetails_DEPRECATED
CMsgReceiveInterAppMessage
k_EGCMsgReceiveInterAppMessage
CMsgFindAccounts
k_EGCMsgFindAccounts
CMsgPostAlert
k_EGCMsgPostAlert
CMsgGetLicenses
k_EGCMsgGetLicenses
CMsgGetUserStats
k_EGCMsgGetUserStats
CMsgGetCommands
k_EGCMsgGetCommands
CMsgGetCommandsResponse
k_EGCMsgGetCommandsResponse
CMsgAddFreeLicense
k_EGCMsgAddFreeLicense
CMsgAddFreeLicenseResponse
k_EGCMsgAddFreeLicenseResponse
CMsgGetIPLocation
k_EGCMsgGetIPLocation
CMsgGetIPLocationResponse
k_EGCMsgGetIPLocationResponse
CMsgSystemStatsSchema
k_EGCMsgSystemStatsSchema
CMsgGetSystemStats
k_EGCMsgGetSystemStats
CMsgGetSystemStatsResponse
k_EGCMsgGetSystemStatsResponse
CMsgSendEmail
k_EGCMsgSendEmail
CMsgSendEmailResponse
k_EGCMsgSendEmailResponse
CMsgGetEmailTemplate
k_EGCMsgGetEmailTemplate
CMsgGetEmailTemplateResponse
k_EGCMsgGetEmailTemplateResponse
CMsgGrantGuestPass
k_EGCMsgGrantGuestPass
CMsgGrantGuestPassResponse
k_EGCMsgGrantGuestPassResponse
CMsgGetAccountDetails
k_EGCMsgGetAccountDetails
CMsgGetAccountDetailsResponse
k_EGCMsgGetAccountDetailsResponse
CMsgGetPersonaNames
k_EGCMsgGetPersonaNames
CMsgGetPersonaNamesResponse
k_EGCMsgGetPersonaNamesResponse
CMsgMultiplexMsg
k_EGCMsgMultiplexMsg
CMsgMultiplexMsgResponse
k_EGCMsgMultiplexMsgResponse
CMsgWebAPIRegisterInterfaces
k_EGCMsgWebAPIRegisterInterfaces
CMsgWebAPIJobRequest
k_EGCMsgWebAPIJobRequest
CMsgWebAPIJobRequestHttpResponse
k_EGCMsgWebAPIJobRequestHttpResponse
CMsgWebAPIJobRequestForwardResponse
k_EGCMsgWebAPIJobRequestForwardResponse
CMsgMemCachedGet
k_EGCMsgMemCachedGet
CMsgMemCachedGetResponse
k_EGCMsgMemCachedGetResponse
CMsgMemCachedSet
k_EGCMsgMemCachedSet
CMsgMemCachedDelete
k_EGCMsgMemCachedDelete
CMsgMemCachedStats
k_EGCMsgMemCachedStats
CMsgMemCachedStatsResponse
k_EGCMsgMemCachedStatsResponse
CMsgMasterSetDirectory
k_EGCMsgMasterSetDirectory
CMsgMasterSetDirectoryResponse
k_EGCMsgMasterSetDirectoryResponse
CMsgMasterSetWebAPIRouting
k_EGCMsgMasterSetWebAPIRouting
CMsgMasterSetWebAPIRoutingResponse
k_EGCMsgMasterSetWebAPIRoutingResponse
CMsgMasterSetClientMsgRouting
k_EGCMsgMasterSetClientMsgRouting
CMsgMasterSetClientMsgRoutingResponse
k_EGCMsgMasterSetClientMsgRoutingResponse
CMsgSetOptions
k_EGCMsgSetOptions
CMsgSetOptionsResponse
k_EGCMsgSetOptionsResponse
CMsgSystemBase2
k_EGCMsgSystemBase2
CMsgGetPurchaseTrustStatus
k_EGCMsgGetPurchaseTrustStatus
CMsgGetPurchaseTrustStatusResponse
k_EGCMsgGetPurchaseTrustStatusResponse
CMsgUpdateSession
k_EGCMsgUpdateSession
CMsgGCAccountVacStatusChange
k_EGCMsgGCAccountVacStatusChange
CMsgCheckFriendship
k_EGCMsgCheckFriendship
CMsgCheckFriendshipResponse
k_EGCMsgCheckFriendshipResponse
CMsgGetPartnerAccountLink
k_EGCMsgGetPartnerAccountLink
CMsgGetPartnerAccountLinkResponse
k_EGCMsgGetPartnerAccountLinkResponse
CMsgDPPartnerMicroTxns
k_EGCMsgDPPartnerMicroTxns
CMsgDPPartnerMicroTxnsResponse
k_EGCMsgDPPartnerMicroTxnsResponse
CMsgVacVerificationChange
k_EGCMsgVacVerificationChange
CMsgAccountPhoneNumberChange
k_EGCMsgAccountPhoneNumberChange
CMsgInviteUserToLobby
k_EGCMsgInviteUserToLobby
CMsgGetGamePersonalDataCategoriesRequest
k_EGCMsgGetGamePersonalDataCategoriesRequest
CMsgGetGamePersonalDataCategoriesResponse
k_EGCMsgGetGamePersonalDataCategoriesResponse
CMsgGetGamePersonalDataEntriesRequest
k_EGCMsgGetGamePersonalDataEntriesRequest
CMsgGetGamePersonalDataEntriesResponse
k_EGCMsgGetGamePersonalDataEntriesResponse
CMsgTerminateGamePersonalDataEntriesRequest
k_EGCMsgTerminateGamePersonalDataEntriesRequest
CMsgTerminateGamePersonalDataEntriesResponse
k_EGCMsgTerminateGamePersonalDataEntriesResponse
CMsgRecurringSubscriptionStatusChange
k_EGCMsgRecurringSubscriptionStatusChange
CMsgDirectServiceMethod
k_EGCMsgDirectServiceMethod
CMsgDirectServiceMethodResponse
k_EGCMsgDirectServiceMethodResponse
k_ESOMsg_Create
k_ESOMsg_Update
k_ESOMsg_Destroy
k_ESOMsg_CacheSubscribed
k_ESOMsg_CacheUnsubscribed
k_ESOMsg_UpdateMultiple
k_ESOMsg_CacheSubscriptionCheck
k_ESOMsg_CacheSubscriptionRefresh
CClientWelcome
k_EMsgGCClientWelcome
CServerWelcome
k_EMsgGCServerWelcome
CClientHello
k_EMsgGCClientHello
CServerHello
k_EMsgGCServerHello
CClientConnectionStatus
k_EMsgGCClientConnectionStatus
CServerConnectionStatus
k_EMsgGCServerConnectionStatus
CClientHelloPartner
k_EMsgGCClientHelloPartner
CClientHelloPW
k_EMsgGCClientHelloPW
CClientHelloR2
k_EMsgGCClientHelloR2
CClientHelloR3
k_EMsgGCClientHelloR3
CClientHelloR4
k_EMsgGCClientHelloR4
k_EGCToGCMsgMasterAck
CMsgMasterAckResponse
k_EGCToGCMsgMasterAckResponse
k_EGCToGCMsgRouted
k_EGCToGCMsgRoutedReply
k_EMsgUpdateSessionIP
k_EMsgRequestSessionIP
k_EMsgRequestSessionIPResponse
k_EGCToGCMsgMasterStartupComplete
k_ECommunityItemClass_Invalid
k_ECommunityItemClass_Badge
k_ECommunityItemClass_GameCard
k_ECommunityItemClass_ProfileBackground
k_ECommunityItemClass_Emoticon
k_ECommunityItemClass_BoosterPack
k_ECommunityItemClass_Consumable
k_ECommunityItemClass_GameGoo
k_ECommunityItemClass_ProfileModifier
k_ECommunityItemClass_Scene
k_ECommunityItemClass_SalienItem
k_ECommunityItemAttribute_Invalid
k_ECommunityItemAttribute_CardBorder
k_ECommunityItemAttribute_Level
k_ECommunityItemAttribute_IssueNumber
k_ECommunityItemAttribute_TradableTime
k_ECommunityItemAttribute_StorePackageID
k_ECommunityItemAttribute_CommunityItemAppID
k_ECommunityItemAttribute_CommunityItemType
k_ECommunityItemAttribute_ProfileModiferEnabled
k_ECommunityItemAttribute_ExpiryTime
CMsgVector
CMsgVector2D
CMsgQAngle
CMsgQuaternion
CMsgTransform
CMsgRGBA
CMsgPlayerInfo
CMsgList_GameEvents
CMsgProtoBufHeader
k_EProtoDebugVisibility_Always
k_EProtoDebugVisibility_Server
k_EProtoDebugVisibility_ValveServer
k_EProtoDebugVisibility_GC
k_EProtoDebugVisibility_Never
CMsgSetItemPositions_ItemPosition
CMsgGCCStrike15_ClientDeepStats_DeepStatsMatch
CMsgGCCStrike15_v2_Predictions_GroupMatchTeamPick
CMsgGCCStrike15_v2_Party_SearchResults_Entry
CMsgLegacySource1ClientWelcome_Location
CMsgGCCStrike15_ClientDeepStats_DeepStatsRange
CMsgGCCStrike15_v2_Fantasy_FantasyTeam
CMsgGCCStrike15_v2_ClientPerfReport_Entry
CMsgGCCStrike15_v2_PremierSeasonSummary_DataPerWeek
CMsgRecurringMissionSchema_MissionTemplateList
CMsgGCCStrike15_v2_GiftsLeaderboardResponse_GiftLeaderboardEntry
CMsgGCCStrike15_v2_Account_RequestCoPlays_Player
CMsgGCCStrike15_v2_MatchmakingServerRoundStats_DropInfo
CMsgGCCStrike15_v2_AccountPrivacySettings_Setting
CMsgGCCStrike15_v2_Fantasy_FantasySlot
CMsgGCCStrike15_v2_ClientPartyWarning_Entry
CMsgGCCStrike15_v2_PremierSeasonSummary_DataPerMap
CMsgClientWelcome_Location
CMsgSerializedSOCache_TypeCache
CMsgSerializedSOCache_Cache
CMsgSOCacheSubscribed_SubscribedType
CMsgSOMultipleObjects_SingleObject
CMsgSerializedSOCache_Cache_Version
CMsgList_GameEvents_event_t
CMsgVector
CMsgVector2D
CMsgQAngle
CMsgQuaternion
CMsgTransform
CMsgRGBA
CMsgPlayerInfo
CMsgList_GameEvents
k_EProtoDebugVisibility_Always
k_EProtoDebugVisibility_Server
k_EProtoDebugVisibility_ValveServer
k_EProtoDebugVisibility_GC
k_EProtoDebugVisibility_Never
CMsgList_GameEvents_event_t
CMsgVector
CMsgVector2D
CMsgQAngle
CMsgQuaternion
CMsgTransform
CMsgRGBA
CMsgPlayerInfo
CMsgList_GameEvents
k_EProtoDebugVisibility_Always
k_EProtoDebugVisibility_Server
k_EProtoDebugVisibility_ValveServer
k_EProtoDebugVisibility_GC
k_EProtoDebugVisibility_Never
CMsgList_GameEvents_event_t
CMsgVector
CMsgVector2D
CMsgQAngle
CMsgQuaternion
CMsgTransform
CMsgRGBA
CMsgPlayerInfo
CMsgList_GameEvents
k_EProtoDebugVisibility_Always
k_EProtoDebugVisibility_Server
k_EProtoDebugVisibility_ValveServer
k_EProtoDebugVisibility_GC
k_EProtoDebugVisibility_Never
CMsgList_GameEvents_event_t
CUserPresetOperation
CMsgVector
CMsgVector2D
CMsgQAngle
CMsgQuaternion
CMsgTransform
CMsgRGBA
CMsgPlayerInfo
CMsgList_GameEvents
k_EProtoDebugVisibility_Always
k_EProtoDebugVisibility_Server
k_EProtoDebugVisibility_ValveServer
k_EProtoDebugVisibility_GC
k_EProtoDebugVisibility_Never
CMsgList_GameEvents_event_t
CUserExtraData
```

### Raw VDF Diff

<details>
<summary>Click to expand</summary>

```diff
--- /dev/null
+++ new
@@ -0,0 +1,1502 @@
+WARNING: setlocale('en_US.UTF-8') failed, using locale: 'C'. International characters may not work.
+Redirecting stderr to '/root/Steam/logs/stderr.txt'
+Logging directory: '/root/Steam/logs'
+[  0%] Checking for available updates...
+[----] Verifying installation...
+UpdateUI: skip show logo
+Steam Console Client (c) Valve Corporation - version 1763795194
+-- type 'quit' to exit --
+Loading Steam API...[0mOK
+[0m
+Connecting anonymously to Steam Public...[0mOK
+[0mWaiting for client config...[0mOK
+[0mWaiting for user info...[0mOK
+[0mAppID : 730, change number : 32852449/0, last change : Thu Dec 18 01:49:24 2025 
+"730"
+{
+	"common"
+	{
+		"clienticon"		"324b323045b09bace182f928f4104dfcd93cb7f3"
+		"clienttga"		"c52076783b94290949b1ab5ac44a84c036c4c313"
+		"name"		"Counter-Strike 2"
+		"languages"
+		{
+			"english"		"1"
+			"german"		"1"
+			"french"		"1"
+			"italian"		"1"
+			"koreana"		"1"
+			"spanish"		"1"
+			"schinese"		"1"
+			"tchinese"		"1"
+			"russian"		"1"
+			"thai"		"1"
+			"japanese"		"1"
+			"portuguese"		"1"
+			"polish"		"1"
+			"danish"		"1"
+			"dutch"		"1"
+			"finnish"		"1"
+			"norwegian"		"1"
+			"swedish"		"1"
+			"hungarian"		"1"
+			"czech"		"1"
+			"romanian"		"1"
+			"turkish"		"1"
+			"brazilian"		"1"
+			"bulgarian"		"1"
+			"greek"		"1"
+			"ukrainian"		"1"
+			"vietnamese"		"1"
+			"latam"		"1"
+			"indonesian"		"1"
+		}
+		"logo"		"d0595ff02f5c79fd19b06f4d6165c3fda2372820"
+		"logo_small"		"d0595ff02f5c79fd19b06f4d6165c3fda2372820_thumb"
+		"icon"		"8dbc71957312bbd3baea65848b545be9eae2a355"
+		"metacritic_url"		""
+		"clienticns"		"a42c6010effb3f108ae59f1b08843d08386e6b2a"
+		"oslist"		"windows,linux"
+		"type"		"Game"
+		"linuxclienticon"		"ff52d4cc462d49c0297b9bc0558b4ef4c3bdd9ae"
+		"exfgls"		"1"
+		"osarch"		""
+		"osextended"		""
+		"steamchinaapproved"		"1"
+		"name_localized"
+		{
+			"sc_schinese"		"反恐精英：全球攻势"
+		}
+		"releasestatesteamchina"		"released"
+		"timeline_marker_updated"		"1765320877"
+		"timeline_marker_svg"		"0eeacc724c77e1f5abeeba4fb542f45bad894470/markers.svg"
+		"market_presence"		"1"
+		"content_descriptors"
+		{
+			"0"		"2"
+			"1"		"5"
+		}
+		"steam_deck_compatibility"
+		{
+			"category"		"2"
+			"steamos_compatibility"		"2"
+			"test_timestamp"		"1708732800"
+			"tested_build_id"		"13439412"
+			"tests"
+			{
+				"0"
+				{
+					"display"		"3"
+					"token"		"#SteamDeckVerified_TestResult_ControllerGlyphsDoNotMatchDeckDevice"
+				}
+				"1"
+				{
+					"display"		"3"
+					"token"		"#SteamDeckVerified_TestResult_InterfaceTextIsNotLegible"
+				}
+				"2"
+				{
+					"display"		"4"
+					"token"		"#SteamDeckVerified_TestResult_DefaultControllerConfigFullyFunctional"
+				}
+				"3"
+				{
+					"display"		"4"
+					"token"		"#SteamDeckVerified_TestResult_DefaultConfigurationIsPerformant"
+				}
+			}
+			"steamos_tests"
+			{
+				"0"
+				{
+					"display"		"3"
+					"token"		"#SteamOS_TestResult_GameStartupFunctional"
+				}
+			}
+			"configuration"
+			{
+				"supported_input"		"gamepad"
+				"requires_manual_keyboard_invoke"		"0"
+				"requires_non_controller_launcher_nav"		"0"
+				"primary_player_is_controller_slot_0"		"0"
+				"non_deck_display_glyphs"		"1"
+				"small_text"		"1"
+				"requires_internet_for_setup"		"0"
+				"requires_internet_for_singleplayer"		"0"
+				"recommended_runtime"		"native"
+				"requires_h264"		"0"
+				"requires_voice_files"		"0"
+				"gamescope_frame_limiter_not_supported"		"0"
+				"hdr_support"		"0"
+			}
+		}
+		"controllertagwizard"		"1"
+		"small_capsule"
+		{
+			"english"		"capsule_231x87.jpg"
+			"sc_schinese"		"capsule_231x87_sc_schinese.jpg"
+			"schinese"		"capsule_231x87_schinese.jpg"
+		}
+		"header_image"
+		{
+			"english"		"header.jpg"
+			"sc_schinese"		"header_sc_schinese.jpg"
+			"schinese"		"header_schinese.jpg"
+		}
+		"library_assets"
+		{
+			"library_capsule"		"en,zh-cn"
+			"library_hero"		"en,zh-cn"
+			"library_logo"		"en,zh-cn"
+			"logo_position"
+			{
+				"pinned_position"		"BottomLeft"
+				"width_pct"		"50.512393149848585"
+				"height_pct"		"99.65280290557178"
+			}
+		}
+		"library_assets_full"
+		{
+			"library_capsule"
+			{
+				"image"
+				{
+					"english"		"library_600x900.jpg"
+					"schinese"		"library_600x900_schinese.jpg"
+				}
+				"image2x"
+				{
+					"english"		"library_600x900_2x.jpg"
+					"schinese"		"library_600x900_schinese_2x.jpg"
+				}
+			}
+			"library_hero"
+			{
+				"image"
+				{
+					"english"		"library_hero.jpg"
+					"schinese"		"library_hero_schinese.jpg"
+				}
+				"image2x"
+				{
+					"english"		"library_hero_2x.jpg"
+					"schinese"		"library_hero_schinese_2x.jpg"
+				}
+			}
+			"library_logo"
+			{
+				"logo_position"
+				{
+					"pinned_position"		"BottomLeft"
+					"width_pct"		"50.512393149848585"
+					"height_pct"		"99.65280290557178"
+				}
+				"image"
+				{
+					"english"		"logo.png"
+					"schinese"		"logo_schinese.png"
+				}
+				"imag
... (truncated)
```

</details>
