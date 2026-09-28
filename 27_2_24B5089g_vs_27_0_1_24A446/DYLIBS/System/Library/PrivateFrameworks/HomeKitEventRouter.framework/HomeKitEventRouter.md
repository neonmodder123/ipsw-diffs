## HomeKitEventRouter

> `/System/Library/PrivateFrameworks/HomeKitEventRouter.framework/HomeKitEventRouter`

```diff

-1516.0.0.0.0
-  __TEXT.__text: 0x16f08
+1493.1.5.1.1
+  __TEXT.__text: 0x16f10
   __TEXT.__objc_methlist: 0x15dc
   __TEXT.__const: 0x48
   __TEXT.__gcc_except_tab: 0x49c
Functions:
~ ___50-[HMEMessageDatagramClient _performConnectRequest]_block_invoke : 564 -> 572
~ ___50-[HMEMessageDatagramClient _performConnectRequest]_block_invoke.10 -> -[HMEMessageDatagramClient _removeRetryTimer] : 764 -> 108
~ -[HMEMessageDatagramClient _didDisconnect] -> ___50-[HMEMessageDatagramClient _performConnectRequest]_block_invoke.10 : 160 -> 764
~ -[HMEMessageDatagramClient _enableRetryTimer] -> -[HMEMessageDatagramClient _didDisconnect] : 564 -> 160
~ -[HMEMessageDatagramClient _performRequestWithBlock:] -> -[HMEMessageDatagramClient _enableRetryTimer] : 188 -> 564
~ ___62-[HMEMessageDatagramClient _performChangeRegistrationsRequest]_block_invoke -> -[HMEMessageDatagramClient _performRequestWithBlock:] : 756 -> 188
~ -[HMEMessageDatagramClient _removeRetryTimer] -> ___62-[HMEMessageDatagramClient _performChangeRegistrationsRequest]_block_invoke : 108 -> 756
```
