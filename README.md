# proguard-beta-issue

```
ProGuard, version 5.3 beta2
Reading program jar [/Users/miloszlewandowski/Desktop/classes.jar]
Reading library jar [/Users/miloszlewandowski/Development/android-sdk-macosx/platforms/android-23/android.jar]
Reading library jar [/Users/miloszlewandowski/Development/android-sdk-macosx/extras/android/m2repository/com/android/support/support-annotations/24.2.0/support-annotations-24.2.0.jar]
Note: the configuration refers to the unknown class 'javax.swing.plaf.ComponentUI'
Note: the configuration refers to the unknown class 'javax.swing.plaf.ComponentUI'
Note: the configuration refers to the unknown class 'javax.swing.JComponent'
Note: there were 3 references to unknown classes.
      You should check your configuration for typos.
      (http://proguard.sourceforge.net/manual/troubleshooting.html#unknownclass)
Note: you're ignoring all warnings!
Unexpected error while computing stack sizes:
  Class       = [com/android/ex/chips/RecipientAlternatesAdapter]
  Method      = [getMatchingRecipients(Landroid/content/Context;Lcom/android/ex/chips/BaseRecipientAdapter;Ljava/util/ArrayList;ILandroid/accounts/Account;Lcom/android/ex/chips/RecipientAlternatesAdapter$RecipientMatchCallback;)V]
  Exception   = [java.lang.IllegalArgumentException] (Stack size becomes negative after instruction [5] astore v6 in [com/android/ex/chips/RecipientAlternatesAdapter.getMatchingRecipients(Landroid/content/Context;Lcom/android/ex/chips/BaseRecipientAdapter;Ljava/util/ArrayList;ILandroid/accounts/Account;Lcom/android/ex/chips/RecipientAlternatesAdapter$RecipientMatchCallback;)V])
Stack size becomes negative after instruction [5] astore v6 in [com/android/ex/chips/RecipientAlternatesAdapter.getMatchingRecipients(Landroid/content/Context;Lcom/android/ex/chips/BaseRecipientAdapter;Ljava/util/ArrayList;ILandroid/accounts/Account;Lcom/android/ex/chips/RecipientAlternatesAdapter$RecipientMatchCallback;)V]
```
