# PowerShellJson
Notes for parsing Json

Working result: 

PS C:\Users\mike.burns> ($json.FormatEntryInfo.ListViewFieldList | Where-Object {$_.PropertyName-like 'Name'}).FormatPropertyField.PropertyValue

PS C:\Users\mike.burns> ($json.FormatEntryInfo.ListViewFieldList | Where-Object {$_.PropertyName-like 'Name'}).FormatPropertyField.PropertyValue[0]

Bypass Spam Filter
PS C:\Users\mike.burns> ($json.FormatEntryInfo.ListViewFieldList | Where-Object {$_.PropertyName-like 'Name'}).FormatPropertyField.PropertyValue[1]

Block Auto-Fowarding
PS C:\Users\mike.burns>


PS C:\Users\mike.burns> $json.FormatEntryInfo.ListViewFieldList


label propertyName                                  formatPropertyField
----- ------------                                  -------------------
      RunspaceId                                    @{propertyValue=aad51bd0-a939-4b6d-99fa-90a2a6aa9986; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      Priority                                      @{propertyValue=0; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      DlpPolicy                                     @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      DlpPolicyId                                   @{propertyValue=00000000-0000-0000-0000-000000000000; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      Comments                                      @{propertyValue=...
      ManuallyModified                              @{propertyValue=False; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ActivationDate                                @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExpiryDate                                    @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      Description                                   @{propertyValue=If the message:...
      RuleVersion                                   @{propertyValue=15.0.1.0; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      Conditions                                    @{propertyValue={Microsoft.Exchange.MessagingPolicies.Rules.Tasks.FromPredicate}; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      Exceptions                                    @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      Actions                                       @{propertyValue={Microsoft.Exchange.MessagingPolicies.Rules.Tasks.SetAuditSeverityAction, Microsoft.Exchange.MessagingPolicies.Rules.Tasks.SetSclAction}; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      State                                         @{propertyValue=Enabled; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      Mode                                          @{propertyValue=Enforce; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      RuleErrorAction                               @{propertyValue=Ignore; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      SenderAddressLocation                         @{propertyValue=Header; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      RecipientAddressType                          @{propertyValue=Resolved; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      RuleSubType                                   @{propertyValue=None; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      UseLegacyRegex                                @{propertyValue=False; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      From                                          @{propertyValue={mike.burns7@gmail.com}; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      FromMemberOf                                  @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      FromScope                                     @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      SentTo                                        @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      SentToMemberOf                                @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      SentToScope                                   @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      BetweenMemberOf1                              @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      BetweenMemberOf2                              @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ManagerAddresses                              @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ManagerForEvaluatedUser                       @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      SenderManagementRelationship                  @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ADComparisonAttribute                         @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ADComparisonOperator                          @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      SenderADAttributeContainsWords                @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      SenderADAttributeMatchesPatterns              @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      RecipientADAttributeContainsWords             @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      RecipientADAttributeMatchesPatterns           @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      AnyOfToHeader                                 @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      AnyOfToHeaderMemberOf                         @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      AnyOfCcHeader                                 @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      AnyOfCcHeaderMemberOf                         @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      AnyOfToCcHeader                               @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      AnyOfToCcHeaderMemberOf                       @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      HasClassification                             @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      HasNoClassification                           @{propertyValue=False; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      SubjectContainsWords                          @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      SubjectOrBodyContainsWords                    @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      HeaderContainsMessageHeader                   @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      HeaderContainsWords                           @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      FromAddressContainsWords                      @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      SenderDomainIs                                @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      RecipientDomainIs                             @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      SubjectMatchesPatterns                        @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      SubjectOrBodyMatchesPatterns                  @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      HeaderMatchesMessageHeader                    @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      HeaderMatchesPatterns                         @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      FromAddressMatchesPatterns                    @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      AttachmentNameMatchesPatterns                 @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      AttachmentExtensionMatchesWords               @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      AttachmentPropertyContainsWords               @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ContentCharacterSetContainsWords              @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      HasSenderOverride                             @{propertyValue=False; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      MessageContainsDataClassifications            @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      MessageContainsAllDataClassifications         @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      SenderIpRanges                                @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      SCLOver                                       @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      AttachmentSizeOver                            @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      MessageSizeOver                               @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      WithImportance                                @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      MessageTypeMatches                            @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      RecipientAddressContainsWords                 @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      RecipientAddressMatchesPatterns               @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      SenderInRecipientList                         @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      RecipientInSenderList                         @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      AttachmentContainsWords                       @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      AttachmentMatchesPatterns                     @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      AttachmentIsUnsupported                       @{propertyValue=False; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      AttachmentProcessingLimitExceeded             @{propertyValue=False; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      AttachmentHasExecutableContent                @{propertyValue=False; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      AttachmentIsPasswordProtected                 @{propertyValue=False; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      AnyOfRecipientAddressContainsWords            @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      AnyOfRecipientAddressMatchesPatterns          @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfFrom                                  @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfFromMemberOf                          @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfFromScope                             @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfSentTo                                @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfSentToMemberOf                        @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfSentToScope                           @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfBetweenMemberOf1                      @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfBetweenMemberOf2                      @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfManagerAddresses                      @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfManagerForEvaluatedUser               @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfSenderManagementRelationship          @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfADComparisonAttribute                 @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfADComparisonOperator                  @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfSenderADAttributeContainsWords        @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfSenderADAttributeMatchesPatterns      @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfRecipientADAttributeContainsWords     @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfRecipientADAttributeMatchesPatterns   @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfAnyOfToHeader                         @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfAnyOfToHeaderMemberOf                 @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfAnyOfCcHeader                         @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfAnyOfCcHeaderMemberOf                 @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfAnyOfToCcHeader                       @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfAnyOfToCcHeaderMemberOf               @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfHasClassification                     @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfHasNoClassification                   @{propertyValue=False; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfSubjectContainsWords                  @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfSubjectOrBodyContainsWords            @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfHeaderContainsMessageHeader           @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfHeaderContainsWords                   @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfFromAddressContainsWords              @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfSenderDomainIs                        @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfRecipientDomainIs                     @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfSubjectMatchesPatterns                @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfSubjectOrBodyMatchesPatterns          @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfHeaderMatchesMessageHeader            @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfHeaderMatchesPatterns                 @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfFromAddressMatchesPatterns            @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfAttachmentNameMatchesPatterns         @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfAttachmentExtensionMatchesWords       @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfAttachmentPropertyContainsWords       @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfContentCharacterSetContainsWords      @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfSCLOver                               @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfAttachmentSizeOver                    @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfMessageSizeOver                       @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfWithImportance                        @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfMessageTypeMatches                    @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfRecipientAddressContainsWords         @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfRecipientAddressMatchesPatterns       @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfSenderInRecipientList                 @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfRecipientInSenderList                 @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfAttachmentContainsWords               @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfAttachmentMatchesPatterns             @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfAttachmentIsUnsupported               @{propertyValue=False; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfAttachmentProcessingLimitExceeded     @{propertyValue=False; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfAttachmentHasExecutableContent        @{propertyValue=False; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfAttachmentIsPasswordProtected         @{propertyValue=False; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfAnyOfRecipientAddressContainsWords    @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfAnyOfRecipientAddressMatchesPatterns  @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfHasSenderOverride                     @{propertyValue=False; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfMessageContainsDataClassifications    @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfMessageContainsAllDataClassifications @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfSenderIpRanges                        @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      PrependSubject                                @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      SetAuditSeverity                              @{propertyValue=Low; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ApplyClassification                           @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ApplyHtmlDisclaimerLocation                   @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ApplyHtmlDisclaimerText                       @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ApplyHtmlDisclaimerFallbackAction             @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ApplyRightsProtectionTemplate                 @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ApplyRightsProtectionCustomizationTemplate    @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      SetSCL                                        @{propertyValue=-1; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      SetHeaderName                                 @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      SetHeaderValue                                @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      RemoveHeader                                  @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      AddToRecipients                               @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      CopyTo                                        @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      BlindCopyTo                                   @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      AddManagerAsRecipientType                     @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ModerateMessageByUser                         @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ModerateMessageByManager                      @{propertyValue=False; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      RedirectMessageTo                             @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      RejectMessageEnhancedStatusCode               @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      RejectMessageReasonText                       @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      DeleteMessage                                 @{propertyValue=False; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      Disconnect                                    @{propertyValue=False; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      Quarantine                                    @{propertyValue=False; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      SmtpRejectMessageRejectText                   @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      SmtpRejectMessageRejectStatusCode             @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      LogEventText                                  @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      StopRuleProcessing                            @{propertyValue=False; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      SenderNotificationType                        @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      GenerateIncidentReport                        @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      IncidentReportContent                         @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      RouteMessageOutboundConnector                 @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      RouteMessageOutboundRequireTls                @{propertyValue=False; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ApplyOME                                      @{propertyValue=False; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      RemoveOME                                     @{propertyValue=False; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      RemoveOMEv2                                   @{propertyValue=False; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      GenerateNotification                          @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      Identity                                      @{propertyValue=Bypass Spam Filter; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      DistinguishedName                             @{propertyValue=CN=Bypass Spam Filter,CN=TransportVersioned,CN=Rules,CN=Transport Settings,CN=Configuration,CN=Burns365.onmicrosoft.com,CN=ConfigurationUnits,DC=NAMPR08A008,DC=PROD,DC=OUTLOOK,DC=COM; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      Guid                                          @{propertyValue=22977eb7-462c-467e-98b0-60ca5f4e0086; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ImmutableId                                   @{propertyValue=22977eb7-462c-467e-98b0-60ca5f4e0086; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      OrganizationId                                @{propertyValue=NAMPR08A008.PROD.OUTLOOK.COM/Microsoft Exchange Hosted Organizations/Burns365.onmicrosoft.com - NAMPR08A008.PROD.OUTLOOK.COM/ConfigurationUnits/Burns365.onmicrosoft.com/Configuration; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      Name                                          @{propertyValue=Bypass Spam Filter; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      IsValid                                       @{propertyValue=True; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      WhenChanged                                   @{propertyValue=6/25/2020 05:01:44; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExchangeVersion                               @{propertyValue=0.1 (8.0.535.0); alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ObjectState                                   @{propertyValue=Unchanged; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      RunspaceId                                    @{propertyValue=aad51bd0-a939-4b6d-99fa-90a2a6aa9986; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      Priority                                      @{propertyValue=1; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      DlpPolicy                                     @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      DlpPolicyId                                   @{propertyValue=00000000-0000-0000-0000-000000000000; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      Comments                                      @{propertyValue=...
      ManuallyModified                              @{propertyValue=False; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ActivationDate                                @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExpiryDate                                    @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      Description                                   @{propertyValue=If the message:...
      RuleVersion                                   @{propertyValue=15.0.5.2; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      Conditions                                    @{propertyValue={Microsoft.Exchange.MessagingPolicies.Rules.Tasks.SentToScopePredicate, Microsoft.Exchange.MessagingPolicies.Rules.Tasks.MessageTypeMatchesPredicate, Microsoft.Exchange.MessagingPolicies.Rules.Tasks.FromScopePredicate}; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9c...
      Exceptions                                    @{propertyValue={Microsoft.Exchange.MessagingPolicies.Rules.Tasks.RecipientDomainIsPredicate}; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      Actions                                       @{propertyValue={Microsoft.Exchange.MessagingPolicies.Rules.Tasks.RejectMessageAction}; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      State                                         @{propertyValue=Enabled; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      Mode                                          @{propertyValue=Enforce; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      RuleErrorAction                               @{propertyValue=Ignore; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      SenderAddressLocation                         @{propertyValue=Header; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      RecipientAddressType                          @{propertyValue=Resolved; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      RuleSubType                                   @{propertyValue=None; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      UseLegacyRegex                                @{propertyValue=False; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      From                                          @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      FromMemberOf                                  @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      FromScope                                     @{propertyValue=InOrganization; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      SentTo                                        @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      SentToMemberOf                                @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      SentToScope                                   @{propertyValue=NotInOrganization; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      BetweenMemberOf1                              @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      BetweenMemberOf2                              @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ManagerAddresses                              @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ManagerForEvaluatedUser                       @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      SenderManagementRelationship                  @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ADComparisonAttribute                         @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ADComparisonOperator                          @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      SenderADAttributeContainsWords                @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      SenderADAttributeMatchesPatterns              @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      RecipientADAttributeContainsWords             @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      RecipientADAttributeMatchesPatterns           @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      AnyOfToHeader                                 @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      AnyOfToHeaderMemberOf                         @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      AnyOfCcHeader                                 @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      AnyOfCcHeaderMemberOf                         @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      AnyOfToCcHeader                               @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      AnyOfToCcHeaderMemberOf                       @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      HasClassification                             @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      HasNoClassification                           @{propertyValue=False; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      SubjectContainsWords                          @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      SubjectOrBodyContainsWords                    @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      HeaderContainsMessageHeader                   @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      HeaderContainsWords                           @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      FromAddressContainsWords                      @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      SenderDomainIs                                @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      RecipientDomainIs                             @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      SubjectMatchesPatterns                        @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      SubjectOrBodyMatchesPatterns                  @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      HeaderMatchesMessageHeader                    @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      HeaderMatchesPatterns                         @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      FromAddressMatchesPatterns                    @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      AttachmentNameMatchesPatterns                 @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      AttachmentExtensionMatchesWords               @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      AttachmentPropertyContainsWords               @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ContentCharacterSetContainsWords              @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      HasSenderOverride                             @{propertyValue=False; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      MessageContainsDataClassifications            @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      MessageContainsAllDataClassifications         @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      SenderIpRanges                                @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      SCLOver                                       @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      AttachmentSizeOver                            @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      MessageSizeOver                               @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      WithImportance                                @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      MessageTypeMatches                            @{propertyValue=AutoForward; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      RecipientAddressContainsWords                 @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      RecipientAddressMatchesPatterns               @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      SenderInRecipientList                         @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      RecipientInSenderList                         @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      AttachmentContainsWords                       @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      AttachmentMatchesPatterns                     @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      AttachmentIsUnsupported                       @{propertyValue=False; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      AttachmentProcessingLimitExceeded             @{propertyValue=False; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      AttachmentHasExecutableContent                @{propertyValue=False; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      AttachmentIsPasswordProtected                 @{propertyValue=False; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      AnyOfRecipientAddressContainsWords            @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      AnyOfRecipientAddressMatchesPatterns          @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfFrom                                  @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfFromMemberOf                          @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfFromScope                             @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfSentTo                                @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfSentToMemberOf                        @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfSentToScope                           @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfBetweenMemberOf1                      @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfBetweenMemberOf2                      @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfManagerAddresses                      @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfManagerForEvaluatedUser               @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfSenderManagementRelationship          @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfADComparisonAttribute                 @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfADComparisonOperator                  @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfSenderADAttributeContainsWords        @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfSenderADAttributeMatchesPatterns      @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfRecipientADAttributeContainsWords     @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfRecipientADAttributeMatchesPatterns   @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfAnyOfToHeader                         @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfAnyOfToHeaderMemberOf                 @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfAnyOfCcHeader                         @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfAnyOfCcHeaderMemberOf                 @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfAnyOfToCcHeader                       @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfAnyOfToCcHeaderMemberOf               @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfHasClassification                     @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfHasNoClassification                   @{propertyValue=False; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfSubjectContainsWords                  @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfSubjectOrBodyContainsWords            @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfHeaderContainsMessageHeader           @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfHeaderContainsWords                   @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfFromAddressContainsWords              @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfSenderDomainIs                        @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfRecipientDomainIs                     @{propertyValue={attack-burns365.com}; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfSubjectMatchesPatterns                @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfSubjectOrBodyMatchesPatterns          @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfHeaderMatchesMessageHeader            @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfHeaderMatchesPatterns                 @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfFromAddressMatchesPatterns            @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfAttachmentNameMatchesPatterns         @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfAttachmentExtensionMatchesWords       @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfAttachmentPropertyContainsWords       @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfContentCharacterSetContainsWords      @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfSCLOver                               @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfAttachmentSizeOver                    @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfMessageSizeOver                       @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfWithImportance                        @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfMessageTypeMatches                    @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfRecipientAddressContainsWords         @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfRecipientAddressMatchesPatterns       @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfSenderInRecipientList                 @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfRecipientInSenderList                 @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfAttachmentContainsWords               @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfAttachmentMatchesPatterns             @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfAttachmentIsUnsupported               @{propertyValue=False; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfAttachmentProcessingLimitExceeded     @{propertyValue=False; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfAttachmentHasExecutableContent        @{propertyValue=False; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfAttachmentIsPasswordProtected         @{propertyValue=False; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfAnyOfRecipientAddressContainsWords    @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfAnyOfRecipientAddressMatchesPatterns  @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfHasSenderOverride                     @{propertyValue=False; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfMessageContainsDataClassifications    @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfMessageContainsAllDataClassifications @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExceptIfSenderIpRanges                        @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      PrependSubject                                @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      SetAuditSeverity                              @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ApplyClassification                           @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ApplyHtmlDisclaimerLocation                   @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ApplyHtmlDisclaimerText                       @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ApplyHtmlDisclaimerFallbackAction             @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ApplyRightsProtectionTemplate                 @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ApplyRightsProtectionCustomizationTemplate    @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      SetSCL                                        @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      SetHeaderName                                 @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      SetHeaderValue                                @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      RemoveHeader                                  @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      AddToRecipients                               @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      CopyTo                                        @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      BlindCopyTo                                   @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      AddManagerAsRecipientType                     @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ModerateMessageByUser                         @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ModerateMessageByManager                      @{propertyValue=False; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      RedirectMessageTo                             @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      RejectMessageEnhancedStatusCode               @{propertyValue=5.7.1; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      RejectMessageReasonText                       @{propertyValue=Auto-Fowarding to External Domains Is Not Permitted; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      DeleteMessage                                 @{propertyValue=False; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      Disconnect                                    @{propertyValue=False; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      Quarantine                                    @{propertyValue=False; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      SmtpRejectMessageRejectText                   @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      SmtpRejectMessageRejectStatusCode             @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      LogEventText                                  @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      StopRuleProcessing                            @{propertyValue=False; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      SenderNotificationType                        @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      GenerateIncidentReport                        @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      IncidentReportContent                         @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      RouteMessageOutboundConnector                 @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      RouteMessageOutboundRequireTls                @{propertyValue=False; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ApplyOME                                      @{propertyValue=False; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      RemoveOME                                     @{propertyValue=False; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      RemoveOMEv2                                   @{propertyValue=False; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      GenerateNotification                          @{propertyValue=; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      Identity                                      @{propertyValue=Block Auto-Fowarding; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      DistinguishedName                             @{propertyValue=CN=Block Auto-Fowarding,CN=TransportVersioned,CN=Rules,CN=Transport Settings,CN=Configuration,CN=Burns365.onmicrosoft.com,CN=ConfigurationUnits,DC=NAMPR08A008,DC=PROD,DC=OUTLOOK,DC=COM; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      Guid                                          @{propertyValue=7b44bb9e-ef22-4dee-b788-abd24409184b; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ImmutableId                                   @{propertyValue=7b44bb9e-ef22-4dee-b788-abd24409184b; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      OrganizationId                                @{propertyValue=NAMPR08A008.PROD.OUTLOOK.COM/Microsoft Exchange Hosted Organizations/Burns365.onmicrosoft.com - NAMPR08A008.PROD.OUTLOOK.COM/ConfigurationUnits/Burns365.onmicrosoft.com/Configuration; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      Name                                          @{propertyValue=Block Auto-Fowarding; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      IsValid                                       @{propertyValue=True; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      WhenChanged                                   @{propertyValue=6/25/2020 05:20:28; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ExchangeVersion                               @{propertyValue=0.1 (8.0.535.0); alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}
      ObjectState                                   @{propertyValue=Unchanged; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}


PS C:\Users\mike.burns> $json.FormatEntryInfo.ListViewFieldList | Where-Object {$._PropertyNamem-like 'Name'}

Where-Object : The term '$._PropertyNamem-like' is not recognized as the name of a cmdlet, function, script file, or operable program. Check the spelling of the name, or if a path was included, verify that the path is correct and try again.
At line:1 char:43
+ ... yInfo.ListViewFieldList | Where-Object {$._PropertyNamem-like 'Name'}
+                               ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
    + CategoryInfo          : ObjectNotFound: ($._PropertyNamem-like:String) [Where-Object], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException,Microsoft.PowerShell.Commands.WhereObjectCommand

PS C:\Users\mike.burns> $json.FormatEntryInfo.ListViewFieldList | Where-Object {$_.PropertyNamem-like 'Name'}

PS C:\Users\mike.burns> $json.FormatEntryInfo.ListViewFieldList | Where-Object {$_.PropertyName-like 'Name'}


label propertyName formatPropertyField                                                                                                          ClassId2e4f51ef21dd47e99d3c952918aff9cd
----- ------------ -------------------                                                                                                          ---------------------------------------
      Name         @{propertyValue=Bypass Spam Filter; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a}   b761477330ce4fb2a665999879324d73
      Name         @{propertyValue=Block Auto-Fowarding; alignment=0; ClassId2e4f51ef21dd47e99d3c952918aff9cd=78b102e894f742aca8c1d6737b6ff86a} b761477330ce4fb2a665999879324d73


PS C:\Users\mike.burns> ($json.FormatEntryInfo.ListViewFieldList | Where-Object {$_.PropertyName-like 'Name'}).PropertyValue

PS C:\Users\mike.burns> ($json.FormatEntryInfo.ListViewFieldList | Where-Object {$_.PropertyName-like 'Name'}).FormatPropertyField


propertyValue        alignment ClassId2e4f51ef21dd47e99d3c952918aff9cd
-------------        --------- ---------------------------------------
Bypass Spam Filter           0 78b102e894f742aca8c1d6737b6ff86a
Block Auto-Fowarding         0 78b102e894f742aca8c1d6737b6ff86a


PS C:\Users\mike.burns> ($json.FormatEntryInfo.ListViewFieldList | Where-Object {$_.PropertyName-like 'Name'}).FormatPropertyField.PropertyValue

Bypass Spam Filter
Block Auto-Fowarding
PS C:\Users\mike.burns>
