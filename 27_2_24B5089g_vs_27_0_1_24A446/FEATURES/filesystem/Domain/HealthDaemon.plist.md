## HealthDaemon.plist

> `Domain/HealthDaemon.plist`

```diff

 <!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
 <plist version="1.0">
 <dict>
-	<key>BatchedRouteSmoothingWatch</key>
+	<key>AllowExperimentalHealthTypesUsage</key>
 	<dict>
 		<key>DevelopmentPhase</key>
 		<string>FeatureComplete</string>
 	</dict>
-	<key>BatchedRouteSmoothingiOS</key>
+	<key>BatchedRouteSmoothingWatch</key>
 	<dict>
 		<key>DevelopmentPhase</key>
 		<string>FeatureComplete</string>

 		<key>DevelopmentPhase</key>
 		<string>FeatureComplete</string>
 	</dict>
-	<key>HeartRateCoordinator</key>
+	<key>HRPassiveSeriesAggregation</key>
 	<dict>
 		<key>DevelopmentPhase</key>
 		<string>FeatureComplete</string>
 	</dict>
-	<key>MaintenanceWorkThroughOrchestration</key>
+	<key>HRWorkoutSeriesAggregation</key>
 	<dict>
 		<key>DevelopmentPhase</key>
 		<string>FeatureComplete</string>
 	</dict>
-	<key>OrchestrationMCDataObservation</key>
+	<key>HeartRateCoordinator</key>
 	<dict>
 		<key>DevelopmentPhase</key>
 		<string>FeatureComplete</string>
 	</dict>
-	<key>SingleTransactionApplySyncChange</key>
+	<key>MaintenanceWorkThroughOrchestration</key>
 	<dict>
 		<key>DevelopmentPhase</key>
 		<string>FeatureComplete</string>
 	</dict>
-	<key>SortedStatisticsSampleMerge</key>
+	<key>OrchestrationMCDataObservation</key>
+	<dict>
+		<key>DevelopmentPhase</key>
+		<string>FeatureComplete</string>
+	</dict>
+	<key>SingleTransactionApplySyncChange</key>
 	<dict>
 		<key>DevelopmentPhase</key>
 		<string>FeatureComplete</string>

 		<key>DevelopmentPhase</key>
 		<string>FeatureComplete</string>
 	</dict>
-	<key>XPCGatedSecondaryJournalMergeForVisionPro</key>
+	<key>WorkoutSeriesAggregation</key>
 	<dict>
 		<key>DevelopmentPhase</key>
 		<string>FeatureComplete</string>
 	</dict>
-	<key>cloudSyncRestoreTask</key>
+	<key>XPCGatedSecondaryJournalMergeForVisionPro</key>
 	<dict>
 		<key>DevelopmentPhase</key>
 		<string>FeatureComplete</string>

```
