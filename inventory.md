# Inventário de Arquivos .tsx do Orca

Este documento apresenta o inventário completo e detalhado de todos os arquivos `.tsx` do projeto Orca, organizados por domínios funcionais e JTBDs (Jobs To Be Done).

**Total de arquivos catalogados:** 1061

## Sumário
- [Desktop App - Core & Routing (3 arquivos)](#desktop-app---core-routing)
- [Desktop App - Workspace & Worktree Management (12 arquivos)](#desktop-app---workspace-worktree-management)
- [Desktop App - Terminal & Execution (37 arquivos)](#desktop-app---terminal-execution)
- [Desktop App - Git & Source Control (6 arquivos)](#desktop-app---git-source-control)
- [Desktop App - Agent Orchestration & Automations (75 arquivos)](#desktop-app---agent-orchestration-automations)
- [Desktop App - Issue Tracking & Integrations (28 arquivos)](#desktop-app---issue-tracking-integrations)
- [Desktop App - Navigation, Tabs & Sidebar Layout (283 arquivos)](#desktop-app---navigation-tabs-sidebar-layout)
- [Desktop App - Status Bar & System Monitoring (20 arquivos)](#desktop-app---status-bar-system-monitoring)
- [Desktop App - Settings & Configuration (205 arquivos)](#desktop-app---settings-configuration)
- [Desktop App - File Editor (Monaco & Markdown) (69 arquivos)](#desktop-app---file-editor-monaco-markdown)
- [Desktop App - Browser & Mobile Emulator Preview (41 arquivos)](#desktop-app---browser-mobile-emulator-preview)
- [Desktop App - Onboarding & Interactive Guides (44 arquivos)](#desktop-app---onboarding-interactive-guides)
- [Desktop App - Dashboard, Stats & System Activity (31 arquivos)](#desktop-app---dashboard-stats-system-activity)
- [Desktop App - UI Primitives (Shadcn) (32 arquivos)](#desktop-app---ui-primitives-shadcn)
- [Desktop App - Shared & Miscellaneous Components (60 arquivos)](#desktop-app---shared-miscellaneous-components)
- [Mobile App - Pages & Routes (22 arquivos)](#mobile-app---pages-routes)
- [Mobile App - UI Components & Features (80 arquivos)](#mobile-app---ui-components-features)
- [Miscellaneous / Other (13 arquivos)](#miscellaneous-other)

---

## Desktop App - Core & Routing

*Total: 3 arquivos*

| Arquivo | Caminho Completo |
| :--- | :--- |
| `App.tsx` | [`src/renderer/src/App.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/App.tsx) |
| `main.tsx` | [`src/renderer/src/main.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/main.tsx) |
| `main.tsx` | [`src/renderer/src/web/main.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/web/main.tsx) |

## Desktop App - Workspace & Worktree Management

*Total: 12 arquivos*

| Arquivo | Caminho Completo |
| :--- | :--- |
| `ProjectCombobox.test.tsx` | [`src/renderer/src/components/new-workspace/ProjectCombobox.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/new-workspace/ProjectCombobox.test.tsx) |
| `ProjectCombobox.tsx` | [`src/renderer/src/components/new-workspace/ProjectCombobox.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/new-workspace/ProjectCombobox.tsx) |
| `ProjectHostSetupCombobox.test.tsx` | [`src/renderer/src/components/new-workspace/ProjectHostSetupCombobox.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/new-workspace/ProjectHostSetupCombobox.test.tsx) |
| `ProjectHostSetupCombobox.tsx` | [`src/renderer/src/components/new-workspace/ProjectHostSetupCombobox.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/new-workspace/ProjectHostSetupCombobox.tsx) |
| `SmartWorkspaceNameField.tsx` | [`src/renderer/src/components/new-workspace/SmartWorkspaceNameField.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/new-workspace/SmartWorkspaceNameField.tsx) |
| `smart-workspace-localized-options.tsx` | [`src/renderer/src/components/new-workspace/smart-workspace-localized-options.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/new-workspace/smart-workspace-localized-options.tsx) |
| `SparseCheckoutPresetDraftForm.tsx` | [`src/renderer/src/components/sparse/SparseCheckoutPresetDraftForm.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sparse/SparseCheckoutPresetDraftForm.tsx) |
| `SparseCheckoutPresetSelect.tsx` | [`src/renderer/src/components/sparse/SparseCheckoutPresetSelect.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sparse/SparseCheckoutPresetSelect.tsx) |
| `WorkspaceCleanupDialog.tsx` | [`src/renderer/src/components/workspace-cleanup/WorkspaceCleanupDialog.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/workspace-cleanup/WorkspaceCleanupDialog.tsx) |
| `WorkspaceSpacePage.tsx` | [`src/renderer/src/components/workspace-space/WorkspaceSpacePage.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/workspace-space/WorkspaceSpacePage.tsx) |
| `WorktreeCreationPanel.test.tsx` | [`src/renderer/src/components/worktree-creation/WorktreeCreationPanel.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/worktree-creation/WorktreeCreationPanel.test.tsx) |
| `WorktreeCreationPanel.tsx` | [`src/renderer/src/components/worktree-creation/WorktreeCreationPanel.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/worktree-creation/WorktreeCreationPanel.tsx) |

## Desktop App - Terminal & Execution

*Total: 37 arquivos*

| Arquivo | Caminho Completo |
| :--- | :--- |
| `FloatingTerminalIconContextMenu.tsx` | [`src/renderer/src/components/floating-terminal/FloatingTerminalIconContextMenu.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/floating-terminal/FloatingTerminalIconContextMenu.tsx) |
| `FloatingTerminalOrchestrationDialog.tsx` | [`src/renderer/src/components/floating-terminal/FloatingTerminalOrchestrationDialog.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/floating-terminal/FloatingTerminalOrchestrationDialog.tsx) |
| `FloatingTerminalPanel.test.tsx` | [`src/renderer/src/components/floating-terminal/FloatingTerminalPanel.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/floating-terminal/FloatingTerminalPanel.test.tsx) |
| `FloatingTerminalPanel.tsx` | [`src/renderer/src/components/floating-terminal/FloatingTerminalPanel.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/floating-terminal/FloatingTerminalPanel.tsx) |
| `FloatingTerminalResizeHandles.tsx` | [`src/renderer/src/components/floating-terminal/FloatingTerminalResizeHandles.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/floating-terminal/FloatingTerminalResizeHandles.tsx) |
| `FloatingTerminalToggleButton.test.tsx` | [`src/renderer/src/components/floating-terminal/FloatingTerminalToggleButton.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/floating-terminal/FloatingTerminalToggleButton.test.tsx) |
| `FloatingTerminalToggleButton.tsx` | [`src/renderer/src/components/floating-terminal/FloatingTerminalToggleButton.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/floating-terminal/FloatingTerminalToggleButton.tsx) |
| `FloatingTerminalWindowControls.tsx` | [`src/renderer/src/components/floating-terminal/FloatingTerminalWindowControls.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/floating-terminal/FloatingTerminalWindowControls.tsx) |
| `CloseTerminalDialog.test.tsx` | [`src/renderer/src/components/terminal-pane/CloseTerminalDialog.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/terminal-pane/CloseTerminalDialog.test.tsx) |
| `CloseTerminalDialog.tsx` | [`src/renderer/src/components/terminal-pane/CloseTerminalDialog.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/terminal-pane/CloseTerminalDialog.tsx) |
| `MobileDriverOverlay.test.tsx` | [`src/renderer/src/components/terminal-pane/MobileDriverOverlay.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/terminal-pane/MobileDriverOverlay.test.tsx) |
| `MobileDriverOverlay.tsx` | [`src/renderer/src/components/terminal-pane/MobileDriverOverlay.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/terminal-pane/MobileDriverOverlay.tsx) |
| `PinnedTabCloseDialog.test.tsx` | [`src/renderer/src/components/terminal-pane/PinnedTabCloseDialog.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/terminal-pane/PinnedTabCloseDialog.test.tsx) |
| `PinnedTabCloseDialog.tsx` | [`src/renderer/src/components/terminal-pane/PinnedTabCloseDialog.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/terminal-pane/PinnedTabCloseDialog.tsx) |
| `SessionRestoredBanner.test.tsx` | [`src/renderer/src/components/terminal-pane/SessionRestoredBanner.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/terminal-pane/SessionRestoredBanner.test.tsx) |
| `SessionRestoredBanner.tsx` | [`src/renderer/src/components/terminal-pane/SessionRestoredBanner.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/terminal-pane/SessionRestoredBanner.tsx) |
| `SessionRestoredBannerPortals.tsx` | [`src/renderer/src/components/terminal-pane/SessionRestoredBannerPortals.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/terminal-pane/SessionRestoredBannerPortals.tsx) |
| `TerminalAgentSessionForkDialog.test.tsx` | [`src/renderer/src/components/terminal-pane/TerminalAgentSessionForkDialog.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/terminal-pane/TerminalAgentSessionForkDialog.test.tsx) |
| `TerminalAgentSessionForkDialog.tsx` | [`src/renderer/src/components/terminal-pane/TerminalAgentSessionForkDialog.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/terminal-pane/TerminalAgentSessionForkDialog.tsx) |
| `TerminalContextMenu.tsx` | [`src/renderer/src/components/terminal-pane/TerminalContextMenu.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/terminal-pane/TerminalContextMenu.tsx) |
| `TerminalErrorToast.tsx` | [`src/renderer/src/components/terminal-pane/TerminalErrorToast.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/terminal-pane/TerminalErrorToast.tsx) |
| `TerminalPane.tsx` | [`src/renderer/src/components/terminal-pane/TerminalPane.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/terminal-pane/TerminalPane.tsx) |
| `TerminalPaneHeaderOverlay.test.tsx` | [`src/renderer/src/components/terminal-pane/TerminalPaneHeaderOverlay.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/terminal-pane/TerminalPaneHeaderOverlay.test.tsx) |
| `TerminalPaneHeaderOverlay.tsx` | [`src/renderer/src/components/terminal-pane/TerminalPaneHeaderOverlay.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/terminal-pane/TerminalPaneHeaderOverlay.tsx) |
| `TerminalPaneOverlayLayer.tsx` | [`src/renderer/src/components/terminal-pane/TerminalPaneOverlayLayer.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/terminal-pane/TerminalPaneOverlayLayer.tsx) |
| `TerminalSessionStateSaveFailureDialog.tsx` | [`src/renderer/src/components/terminal-pane/TerminalSessionStateSaveFailureDialog.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/terminal-pane/TerminalSessionStateSaveFailureDialog.tsx) |
| `session-restored-banner-pane-state.test.tsx` | [`src/renderer/src/components/terminal-pane/session-restored-banner-pane-state.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/terminal-pane/session-restored-banner-pane-state.test.tsx) |
| `useSessionRestoredBannerDismiss.test.tsx` | [`src/renderer/src/components/terminal-pane/useSessionRestoredBannerDismiss.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/terminal-pane/useSessionRestoredBannerDismiss.test.tsx) |
| `TerminalQuickCommandActionToggle.tsx` | [`src/renderer/src/components/terminal-quick-commands/TerminalQuickCommandActionToggle.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/terminal-quick-commands/TerminalQuickCommandActionToggle.tsx) |
| `TerminalQuickCommandAdvancedSection.tsx` | [`src/renderer/src/components/terminal-quick-commands/TerminalQuickCommandAdvancedSection.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/terminal-quick-commands/TerminalQuickCommandAdvancedSection.tsx) |
| `TerminalQuickCommandAppendEnterSwitch.tsx` | [`src/renderer/src/components/terminal-quick-commands/TerminalQuickCommandAppendEnterSwitch.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/terminal-quick-commands/TerminalQuickCommandAppendEnterSwitch.tsx) |
| `TerminalQuickCommandContentSection.tsx` | [`src/renderer/src/components/terminal-quick-commands/TerminalQuickCommandContentSection.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/terminal-quick-commands/TerminalQuickCommandContentSection.tsx) |
| `TerminalQuickCommandDialog.test.tsx` | [`src/renderer/src/components/terminal-quick-commands/TerminalQuickCommandDialog.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/terminal-quick-commands/TerminalQuickCommandDialog.test.tsx) |
| `TerminalQuickCommandDialog.tsx` | [`src/renderer/src/components/terminal-quick-commands/TerminalQuickCommandDialog.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/terminal-quick-commands/TerminalQuickCommandDialog.tsx) |
| `TerminalQuickCommandDialogFooter.tsx` | [`src/renderer/src/components/terminal-quick-commands/TerminalQuickCommandDialogFooter.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/terminal-quick-commands/TerminalQuickCommandDialogFooter.tsx) |
| `TerminalQuickCommandLabelField.tsx` | [`src/renderer/src/components/terminal-quick-commands/TerminalQuickCommandLabelField.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/terminal-quick-commands/TerminalQuickCommandLabelField.tsx) |
| `TerminalQuickCommandScopeField.tsx` | [`src/renderer/src/components/terminal-quick-commands/TerminalQuickCommandScopeField.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/terminal-quick-commands/TerminalQuickCommandScopeField.tsx) |

## Desktop App - Git & Source Control

*Total: 6 arquivos*

| Arquivo | Caminho Completo |
| :--- | :--- |
| `DiffCommentCard.tsx` | [`src/renderer/src/components/diff-comments/DiffCommentCard.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/diff-comments/DiffCommentCard.tsx) |
| `DiffCommentPopover.tsx` | [`src/renderer/src/components/diff-comments/DiffCommentPopover.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/diff-comments/DiffCommentPopover.tsx) |
| `diff-comment-popover-outside-click.test.tsx` | [`src/renderer/src/components/diff-comments/diff-comment-popover-outside-click.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/diff-comments/diff-comment-popover-outside-click.test.tsx) |
| `useDiffCommentDecorator.tsx` | [`src/renderer/src/components/diff-comments/useDiffCommentDecorator.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/diff-comments/useDiffCommentDecorator.tsx) |
| `SourceControlActionVariableChips.test.tsx` | [`src/renderer/src/components/source-control/SourceControlActionVariableChips.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/source-control/SourceControlActionVariableChips.test.tsx) |
| `SourceControlActionVariableChips.tsx` | [`src/renderer/src/components/source-control/SourceControlActionVariableChips.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/source-control/SourceControlActionVariableChips.tsx) |

## Desktop App - Agent Orchestration & Automations

*Total: 75 arquivos*

| Arquivo | Caminho Completo |
| :--- | :--- |
| `AgentCombobox.test.tsx` | [`src/renderer/src/components/agent/AgentCombobox.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/agent/AgentCombobox.test.tsx) |
| `AgentCombobox.tsx` | [`src/renderer/src/components/agent/AgentCombobox.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/agent/AgentCombobox.tsx) |
| `AgentSettingsDialog.tsx` | [`src/renderer/src/components/agent/AgentSettingsDialog.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/agent/AgentSettingsDialog.tsx) |
| `AutomationCustomCronPanel.tsx` | [`src/renderer/src/components/automations/AutomationCustomCronPanel.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/automations/AutomationCustomCronPanel.tsx) |
| `AutomationDetail.tsx` | [`src/renderer/src/components/automations/AutomationDetail.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/automations/AutomationDetail.tsx) |
| `AutomationEditorDialog.tsx` | [`src/renderer/src/components/automations/AutomationEditorDialog.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/automations/AutomationEditorDialog.tsx) |
| `AutomationEditorDialogFooter.tsx` | [`src/renderer/src/components/automations/AutomationEditorDialogFooter.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/automations/AutomationEditorDialogFooter.tsx) |
| `AutomationEditorDialogHeader.tsx` | [`src/renderer/src/components/automations/AutomationEditorDialogHeader.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/automations/AutomationEditorDialogHeader.tsx) |
| `AutomationEditorPromptSection.tsx` | [`src/renderer/src/components/automations/AutomationEditorPromptSection.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/automations/AutomationEditorPromptSection.tsx) |
| `AutomationMissedRunGraceField.tsx` | [`src/renderer/src/components/automations/AutomationMissedRunGraceField.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/automations/AutomationMissedRunGraceField.tsx) |
| `AutomationPrecheckFields.tsx` | [`src/renderer/src/components/automations/AutomationPrecheckFields.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/automations/AutomationPrecheckFields.tsx) |
| `AutomationProjectCombobox.tsx` | [`src/renderer/src/components/automations/AutomationProjectCombobox.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/automations/AutomationProjectCombobox.tsx) |
| `AutomationRunHistory.tsx` | [`src/renderer/src/components/automations/AutomationRunHistory.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/automations/AutomationRunHistory.tsx) |
| `AutomationRunPageFrame.tsx` | [`src/renderer/src/components/automations/AutomationRunPageFrame.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/automations/AutomationRunPageFrame.tsx) |
| `AutomationSchedulePicker.tsx` | [`src/renderer/src/components/automations/AutomationSchedulePicker.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/automations/AutomationSchedulePicker.tsx) |
| `AutomationSessionField.tsx` | [`src/renderer/src/components/automations/AutomationSessionField.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/automations/AutomationSessionField.tsx) |
| `AutomationsPage.tsx` | [`src/renderer/src/components/automations/AutomationsPage.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/automations/AutomationsPage.tsx) |
| `CreateFromPicker.test.tsx` | [`src/renderer/src/components/automations/CreateFromPicker.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/automations/CreateFromPicker.test.tsx) |
| `CreateFromPicker.tsx` | [`src/renderer/src/components/automations/CreateFromPicker.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/automations/CreateFromPicker.tsx) |
| `ExternalAutomationManagers.tsx` | [`src/renderer/src/components/automations/ExternalAutomationManagers.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/automations/ExternalAutomationManagers.tsx) |
| `ExternalAutomationRunTable.tsx` | [`src/renderer/src/components/automations/ExternalAutomationRunTable.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/automations/ExternalAutomationRunTable.tsx) |
| `HermesCronOutputView.tsx` | [`src/renderer/src/components/automations/HermesCronOutputView.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/automations/HermesCronOutputView.tsx) |
| `WorkspaceCombobox.tsx` | [`src/renderer/src/components/automations/WorkspaceCombobox.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/automations/WorkspaceCombobox.tsx) |
| `automation-page-parts.tsx` | [`src/renderer/src/components/automations/automation-page-parts.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/automations/automation-page-parts.tsx) |
| `AgentCapabilitiesSetupAction.tsx` | [`src/renderer/src/components/feature-wall/AgentCapabilitiesSetupAction.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/feature-wall/AgentCapabilitiesSetupAction.tsx) |
| `AgentsOrchestrationVisual.tsx` | [`src/renderer/src/components/feature-wall/AgentsOrchestrationVisual.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/feature-wall/AgentsOrchestrationVisual.tsx) |
| `AiCommitPrSettingsCard.tsx` | [`src/renderer/src/components/feature-wall/AiCommitPrSettingsCard.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/feature-wall/AiCommitPrSettingsCard.tsx) |
| `AiCommitPrSettingsFields.tsx` | [`src/renderer/src/components/feature-wall/AiCommitPrSettingsFields.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/feature-wall/AiCommitPrSettingsFields.tsx) |
| `AiCommitPrSettingsSwitch.tsx` | [`src/renderer/src/components/feature-wall/AiCommitPrSettingsSwitch.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/feature-wall/AiCommitPrSettingsSwitch.tsx) |
| `BrowserAnimatedVisual.tsx` | [`src/renderer/src/components/feature-wall/BrowserAnimatedVisual.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/feature-wall/BrowserAnimatedVisual.tsx) |
| `BrowserUseSkillSetupCard.tsx` | [`src/renderer/src/components/feature-wall/BrowserUseSkillSetupCard.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/feature-wall/BrowserUseSkillSetupCard.tsx) |
| `ComputerUseAnimatedVisual.tsx` | [`src/renderer/src/components/feature-wall/ComputerUseAnimatedVisual.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/feature-wall/ComputerUseAnimatedVisual.tsx) |
| `ConnectIntegrationsList.test.tsx` | [`src/renderer/src/components/feature-wall/ConnectIntegrationsList.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/feature-wall/ConnectIntegrationsList.test.tsx) |
| `ConnectIntegrationsList.tsx` | [`src/renderer/src/components/feature-wall/ConnectIntegrationsList.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/feature-wall/ConnectIntegrationsList.tsx) |
| `EditorAnimatedVisual.tsx` | [`src/renderer/src/components/feature-wall/EditorAnimatedVisual.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/feature-wall/EditorAnimatedVisual.tsx) |
| `FeatureTourPreview.test.tsx` | [`src/renderer/src/components/feature-wall/FeatureTourPreview.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/feature-wall/FeatureTourPreview.test.tsx) |
| `FeatureTourPreview.tsx` | [`src/renderer/src/components/feature-wall/FeatureTourPreview.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/feature-wall/FeatureTourPreview.tsx) |
| `FeatureTourTerminalFrame.tsx` | [`src/renderer/src/components/feature-wall/FeatureTourTerminalFrame.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/feature-wall/FeatureTourTerminalFrame.tsx) |
| `FeatureTourWorkspaceCard.tsx` | [`src/renderer/src/components/feature-wall/FeatureTourWorkspaceCard.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/feature-wall/FeatureTourWorkspaceCard.tsx) |
| `FeatureWallBody.tsx` | [`src/renderer/src/components/feature-wall/FeatureWallBody.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/feature-wall/FeatureWallBody.tsx) |
| `FeatureWallBrowserAction.tsx` | [`src/renderer/src/components/feature-wall/FeatureWallBrowserAction.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/feature-wall/FeatureWallBrowserAction.tsx) |
| `FeatureWallClickRing.tsx` | [`src/renderer/src/components/feature-wall/FeatureWallClickRing.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/feature-wall/FeatureWallClickRing.tsx) |
| `FeatureWallContinueButton.tsx` | [`src/renderer/src/components/feature-wall/FeatureWallContinueButton.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/feature-wall/FeatureWallContinueButton.tsx) |
| `FeatureWallModal.tsx` | [`src/renderer/src/components/feature-wall/FeatureWallModal.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/feature-wall/FeatureWallModal.tsx) |
| `FeatureWallPreview.tsx` | [`src/renderer/src/components/feature-wall/FeatureWallPreview.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/feature-wall/FeatureWallPreview.tsx) |
| `FeatureWallRail.tsx` | [`src/renderer/src/components/feature-wall/FeatureWallRail.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/feature-wall/FeatureWallRail.tsx) |
| `FeatureWallSetupChecklist.tsx` | [`src/renderer/src/components/feature-wall/FeatureWallSetupChecklist.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/feature-wall/FeatureWallSetupChecklist.tsx) |
| `FeatureWallSetupStepVisuals.tsx` | [`src/renderer/src/components/feature-wall/FeatureWallSetupStepVisuals.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/feature-wall/FeatureWallSetupStepVisuals.tsx) |
| `FeatureWallSetupWorkflowActions.test.tsx` | [`src/renderer/src/components/feature-wall/FeatureWallSetupWorkflowActions.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/feature-wall/FeatureWallSetupWorkflowActions.test.tsx) |
| `FeatureWallSetupWorkflowActions.tsx` | [`src/renderer/src/components/feature-wall/FeatureWallSetupWorkflowActions.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/feature-wall/FeatureWallSetupWorkflowActions.tsx) |
| `FeatureWallTourPanel.tsx` | [`src/renderer/src/components/feature-wall/FeatureWallTourPanel.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/feature-wall/FeatureWallTourPanel.tsx) |
| `FeatureWallTourSurface.tsx` | [`src/renderer/src/components/feature-wall/FeatureWallTourSurface.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/feature-wall/FeatureWallTourSurface.tsx) |
| `FullDiskAccessSetupPrompt.tsx` | [`src/renderer/src/components/feature-wall/FullDiskAccessSetupPrompt.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/feature-wall/FullDiskAccessSetupPrompt.tsx) |
| `KeepAwakeCard.tsx` | [`src/renderer/src/components/feature-wall/KeepAwakeCard.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/feature-wall/KeepAwakeCard.tsx) |
| `ReviewAnimatedVisual.tsx` | [`src/renderer/src/components/feature-wall/ReviewAnimatedVisual.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/feature-wall/ReviewAnimatedVisual.tsx) |
| `ReviewNotesAnimatedVisual.tsx` | [`src/renderer/src/components/feature-wall/ReviewNotesAnimatedVisual.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/feature-wall/ReviewNotesAnimatedVisual.tsx) |
| `ReviewPRViewAnimatedVisual.tsx` | [`src/renderer/src/components/feature-wall/ReviewPRViewAnimatedVisual.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/feature-wall/ReviewPRViewAnimatedVisual.tsx) |
| `ReviewShipAnimatedVisual.tsx` | [`src/renderer/src/components/feature-wall/ReviewShipAnimatedVisual.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/feature-wall/ReviewShipAnimatedVisual.tsx) |
| `TasksAnimatedVisual.tsx` | [`src/renderer/src/components/feature-wall/TasksAnimatedVisual.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/feature-wall/TasksAnimatedVisual.tsx) |
| `WorkbenchAnimatedVisual.tsx` | [`src/renderer/src/components/feature-wall/WorkbenchAnimatedVisual.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/feature-wall/WorkbenchAnimatedVisual.tsx) |
| `WorkspacesAnimatedVisual.tsx` | [`src/renderer/src/components/feature-wall/WorkspacesAnimatedVisual.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/feature-wall/WorkspacesAnimatedVisual.tsx) |
| `OrchestrationPage.tsx` | [`src/renderer/src/components/feature-wall/agents-orchestration/OrchestrationPage.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/feature-wall/agents-orchestration/OrchestrationPage.tsx) |
| `StatusesPage.tsx` | [`src/renderer/src/components/feature-wall/agents-orchestration/StatusesPage.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/feature-wall/agents-orchestration/StatusesPage.tsx) |
| `UsageAccountsCard.tsx` | [`src/renderer/src/components/feature-wall/agents-orchestration/UsageAccountsCard.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/feature-wall/agents-orchestration/UsageAccountsCard.tsx) |
| `UsagePage.tsx` | [`src/renderer/src/components/feature-wall/agents-orchestration/UsagePage.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/feature-wall/agents-orchestration/UsagePage.tsx) |
| `orchestration-cards.tsx` | [`src/renderer/src/components/feature-wall/agents-orchestration/orchestration-cards.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/feature-wall/agents-orchestration/orchestration-cards.tsx) |
| `connect-integration-step.tsx` | [`src/renderer/src/components/feature-wall/connect-integration-step.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/feature-wall/connect-integration-step.tsx) |
| `feature-tour-preview-glyphs.tsx` | [`src/renderer/src/components/feature-wall/feature-tour-preview-glyphs.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/feature-wall/feature-tour-preview-glyphs.tsx) |
| `feature-wall-shortcut-labels.test.tsx` | [`src/renderer/src/components/feature-wall/feature-wall-shortcut-labels.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/feature-wall/feature-wall-shortcut-labels.test.tsx) |
| `review-animated-visual-notes-styles.tsx` | [`src/renderer/src/components/feature-wall/review-animated-visual-notes-styles.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/feature-wall/review-animated-visual-notes-styles.tsx) |
| `review-animated-visual-pr-view-styles.tsx` | [`src/renderer/src/components/feature-wall/review-animated-visual-pr-view-styles.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/feature-wall/review-animated-visual-pr-view-styles.tsx) |
| `review-animated-visual-shared.tsx` | [`src/renderer/src/components/feature-wall/review-animated-visual-shared.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/feature-wall/review-animated-visual-shared.tsx) |
| `review-animated-visual-ship-styles.tsx` | [`src/renderer/src/components/feature-wall/review-animated-visual-ship-styles.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/feature-wall/review-animated-visual-ship-styles.tsx) |
| `review-notes-diff-rows.tsx` | [`src/renderer/src/components/feature-wall/review-notes-diff-rows.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/feature-wall/review-notes-diff-rows.tsx) |
| `SkillsPage.tsx` | [`src/renderer/src/components/skills/SkillsPage.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/skills/SkillsPage.tsx) |

## Desktop App - Issue Tracking & Integrations

*Total: 28 arquivos*

| Arquivo | Caminho Completo |
| :--- | :--- |
| `ColumnResizeHandle.tsx` | [`src/renderer/src/components/github-project/ColumnResizeHandle.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/github-project/ColumnResizeHandle.tsx) |
| `GhAuthErrorHelp.tsx` | [`src/renderer/src/components/github-project/GhAuthErrorHelp.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/github-project/GhAuthErrorHelp.tsx) |
| `ProjectCell.tsx` | [`src/renderer/src/components/github-project/ProjectCell.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/github-project/ProjectCell.tsx) |
| `ProjectGroupHeader.tsx` | [`src/renderer/src/components/github-project/ProjectGroupHeader.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/github-project/ProjectGroupHeader.tsx) |
| `ProjectItemSlugDialog.tsx` | [`src/renderer/src/components/github-project/ProjectItemSlugDialog.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/github-project/ProjectItemSlugDialog.tsx) |
| `ProjectPicker.tsx` | [`src/renderer/src/components/github-project/ProjectPicker.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/github-project/ProjectPicker.tsx) |
| `ProjectRow.tsx` | [`src/renderer/src/components/github-project/ProjectRow.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/github-project/ProjectRow.tsx) |
| `ProjectViewList.tsx` | [`src/renderer/src/components/github-project/ProjectViewList.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/github-project/ProjectViewList.tsx) |
| `ProjectViewWrapper.tsx` | [`src/renderer/src/components/github-project/ProjectViewWrapper.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/github-project/ProjectViewWrapper.tsx) |
| `AssigneesEditor.tsx` | [`src/renderer/src/components/github-project/slug-dialog/AssigneesEditor.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/github-project/slug-dialog/AssigneesEditor.tsx) |
| `Comments.tsx` | [`src/renderer/src/components/github-project/slug-dialog/Comments.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/github-project/slug-dialog/Comments.tsx) |
| `LabelsEditor.tsx` | [`src/renderer/src/components/github-project/slug-dialog/LabelsEditor.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/github-project/slug-dialog/LabelsEditor.tsx) |
| `SlugDialogBody.tsx` | [`src/renderer/src/components/github-project/slug-dialog/SlugDialogBody.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/github-project/slug-dialog/SlugDialogBody.tsx) |
| `CloseReasonDropdown.tsx` | [`src/renderer/src/components/github/CloseReasonDropdown.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/github/CloseReasonDropdown.tsx) |
| `GitHubIssueCommentComposer.tsx` | [`src/renderer/src/components/github/GitHubIssueCommentComposer.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/github/GitHubIssueCommentComposer.tsx) |
| `GitHubMarkdownComposer.tsx` | [`src/renderer/src/components/github/GitHubMarkdownComposer.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/github/GitHubMarkdownComposer.tsx) |
| `GitHubWorkItemAssigneePopoverContent.tsx` | [`src/renderer/src/components/github/GitHubWorkItemAssigneePopoverContent.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/github/GitHubWorkItemAssigneePopoverContent.tsx) |
| `GitHubWorkItemLabelPopoverContent.tsx` | [`src/renderer/src/components/github/GitHubWorkItemLabelPopoverContent.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/github/GitHubWorkItemLabelPopoverContent.tsx) |
| `IssueSourceIndicator.tsx` | [`src/renderer/src/components/github/IssueSourceIndicator.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/github/IssueSourceIndicator.tsx) |
| `IssueSourceSelector.tsx` | [`src/renderer/src/components/github/IssueSourceSelector.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/github/IssueSourceSelector.tsx) |
| `PRFilterDropdowns.tsx` | [`src/renderer/src/components/github/PRFilterDropdowns.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/github/PRFilterDropdowns.tsx) |
| `PRFilterPickers.tsx` | [`src/renderer/src/components/github/PRFilterPickers.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/github/PRFilterPickers.tsx) |
| `PRFilterSections.tsx` | [`src/renderer/src/components/github/PRFilterSections.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/github/PRFilterSections.tsx) |
| `github-issue-close-reasons.tsx` | [`src/renderer/src/components/github/github-issue-close-reasons.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/github/github-issue-close-reasons.tsx) |
| `github-markdown-composer-preview-pane.tsx` | [`src/renderer/src/components/github/github-markdown-composer-preview-pane.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/github/github-markdown-composer-preview-pane.tsx) |
| `github-markdown-composer-tabbar.tsx` | [`src/renderer/src/components/github/github-markdown-composer-tabbar.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/github/github-markdown-composer-tabbar.tsx) |
| `github-rate-limit-display.tsx` | [`src/renderer/src/components/github/github-rate-limit-display.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/github/github-rate-limit-display.tsx) |
| `gitlab-rate-limit-display.tsx` | [`src/renderer/src/components/gitlab/gitlab-rate-limit-display.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/gitlab/gitlab-rate-limit-display.tsx) |

## Desktop App - Navigation, Tabs & Sidebar Layout

*Total: 283 arquivos*

| Arquivo | Caminho Completo |
| :--- | :--- |
| `ActionButton.test.tsx` | [`src/renderer/src/components/right-sidebar/ActionButton.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/right-sidebar/ActionButton.test.tsx) |
| `AiVaultPanel.tsx` | [`src/renderer/src/components/right-sidebar/AiVaultPanel.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/right-sidebar/AiVaultPanel.tsx) |
| `AiVaultPanelControls.tsx` | [`src/renderer/src/components/right-sidebar/AiVaultPanelControls.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/right-sidebar/AiVaultPanelControls.tsx) |
| `AiVaultPanelHeader.tsx` | [`src/renderer/src/components/right-sidebar/AiVaultPanelHeader.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/right-sidebar/AiVaultPanelHeader.tsx) |
| `AiVaultSessionDetails.tsx` | [`src/renderer/src/components/right-sidebar/AiVaultSessionDetails.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/right-sidebar/AiVaultSessionDetails.tsx) |
| `AiVaultSessionRow.tsx` | [`src/renderer/src/components/right-sidebar/AiVaultSessionRow.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/right-sidebar/AiVaultSessionRow.tsx) |
| `AiVaultSessionVirtualList.tsx` | [`src/renderer/src/components/right-sidebar/AiVaultSessionVirtualList.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/right-sidebar/AiVaultSessionVirtualList.tsx) |
| `BulkActionBar.tsx` | [`src/renderer/src/components/right-sidebar/BulkActionBar.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/right-sidebar/BulkActionBar.tsx) |
| `ChecksPanel.review-header.test.tsx` | [`src/renderer/src/components/right-sidebar/ChecksPanel.review-header.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/right-sidebar/ChecksPanel.review-header.test.tsx) |
| `ChecksPanel.tsx` | [`src/renderer/src/components/right-sidebar/ChecksPanel.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/right-sidebar/ChecksPanel.tsx) |
| `ChecksPanel.updated-at-metadata.test.tsx` | [`src/renderer/src/components/right-sidebar/ChecksPanel.updated-at-metadata.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/right-sidebar/ChecksPanel.updated-at-metadata.test.tsx) |
| `CommitArea.chevron-spinner.test.tsx` | [`src/renderer/src/components/right-sidebar/CommitArea.chevron-spinner.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/right-sidebar/CommitArea.chevron-spinner.test.tsx) |
| `CommitArea.generate.test.tsx` | [`src/renderer/src/components/right-sidebar/CommitArea.generate.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/right-sidebar/CommitArea.generate.test.tsx) |
| `CommitArea.primary-icons.test.tsx` | [`src/renderer/src/components/right-sidebar/CommitArea.primary-icons.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/right-sidebar/CommitArea.primary-icons.test.tsx) |
| `CommitArea.test.tsx` | [`src/renderer/src/components/right-sidebar/CommitArea.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/right-sidebar/CommitArea.test.tsx) |
| `CreateHostedReviewComposer.tsx` | [`src/renderer/src/components/right-sidebar/CreateHostedReviewComposer.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/right-sidebar/CreateHostedReviewComposer.tsx) |
| `CreateHostedReviewComposerFields.tsx` | [`src/renderer/src/components/right-sidebar/CreateHostedReviewComposerFields.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/right-sidebar/CreateHostedReviewComposerFields.tsx) |
| `CreatePullRequestDialog.tsx` | [`src/renderer/src/components/right-sidebar/CreatePullRequestDialog.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/right-sidebar/CreatePullRequestDialog.tsx) |
| `CreatePullRequestDialogForm.tsx` | [`src/renderer/src/components/right-sidebar/CreatePullRequestDialogForm.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/right-sidebar/CreatePullRequestDialogForm.tsx) |
| `CreatePullRequestGenerateButton.tsx` | [`src/renderer/src/components/right-sidebar/CreatePullRequestGenerateButton.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/right-sidebar/CreatePullRequestGenerateButton.tsx) |
| `FileExplorer.test.tsx` | [`src/renderer/src/components/right-sidebar/FileExplorer.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/right-sidebar/FileExplorer.test.tsx) |
| `FileExplorer.tsx` | [`src/renderer/src/components/right-sidebar/FileExplorer.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/right-sidebar/FileExplorer.tsx) |
| `FileExplorerBackgroundMenu.tsx` | [`src/renderer/src/components/right-sidebar/FileExplorerBackgroundMenu.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/right-sidebar/FileExplorerBackgroundMenu.tsx) |
| `FileExplorerNameFilter.tsx` | [`src/renderer/src/components/right-sidebar/FileExplorerNameFilter.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/right-sidebar/FileExplorerNameFilter.tsx) |
| `FileExplorerQueryStrip.tsx` | [`src/renderer/src/components/right-sidebar/FileExplorerQueryStrip.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/right-sidebar/FileExplorerQueryStrip.tsx) |
| `FileExplorerRow.tsx` | [`src/renderer/src/components/right-sidebar/FileExplorerRow.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/right-sidebar/FileExplorerRow.tsx) |
| `FileExplorerToolbar.tsx` | [`src/renderer/src/components/right-sidebar/FileExplorerToolbar.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/right-sidebar/FileExplorerToolbar.tsx) |
| `FileExplorerTreeStatus.tsx` | [`src/renderer/src/components/right-sidebar/FileExplorerTreeStatus.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/right-sidebar/FileExplorerTreeStatus.tsx) |
| `FileExplorerViewSwitch.tsx` | [`src/renderer/src/components/right-sidebar/FileExplorerViewSwitch.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/right-sidebar/FileExplorerViewSwitch.tsx) |
| `FileExplorerVirtualRows.tsx` | [`src/renderer/src/components/right-sidebar/FileExplorerVirtualRows.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/right-sidebar/FileExplorerVirtualRows.tsx) |
| `FileExplorerVirtualRowsAddProject.test.tsx` | [`src/renderer/src/components/right-sidebar/FileExplorerVirtualRowsAddProject.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/right-sidebar/FileExplorerVirtualRowsAddProject.test.tsx) |
| `FolderWorkspacePrChecksPanel.test.tsx` | [`src/renderer/src/components/right-sidebar/FolderWorkspacePrChecksPanel.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/right-sidebar/FolderWorkspacePrChecksPanel.test.tsx) |
| `FolderWorkspacePrChecksPanel.tsx` | [`src/renderer/src/components/right-sidebar/FolderWorkspacePrChecksPanel.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/right-sidebar/FolderWorkspacePrChecksPanel.tsx) |
| `FolderWorkspacePrChecksRow.test.tsx` | [`src/renderer/src/components/right-sidebar/FolderWorkspacePrChecksRow.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/right-sidebar/FolderWorkspacePrChecksRow.test.tsx) |
| `FolderWorkspacePrChecksRow.tsx` | [`src/renderer/src/components/right-sidebar/FolderWorkspacePrChecksRow.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/right-sidebar/FolderWorkspacePrChecksRow.tsx) |
| `FolderWorkspaceWorktreesPanel.test.tsx` | [`src/renderer/src/components/right-sidebar/FolderWorkspaceWorktreesPanel.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/right-sidebar/FolderWorkspaceWorktreesPanel.test.tsx) |
| `FolderWorkspaceWorktreesPanel.tsx` | [`src/renderer/src/components/right-sidebar/FolderWorkspaceWorktreesPanel.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/right-sidebar/FolderWorkspaceWorktreesPanel.tsx) |
| `GitHistoryCommitContextMenu.tsx` | [`src/renderer/src/components/right-sidebar/GitHistoryCommitContextMenu.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/right-sidebar/GitHistoryCommitContextMenu.tsx) |
| `GitHistoryCommitFiles.tsx` | [`src/renderer/src/components/right-sidebar/GitHistoryCommitFiles.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/right-sidebar/GitHistoryCommitFiles.tsx) |
| `GitHistoryGraphSvg.tsx` | [`src/renderer/src/components/right-sidebar/GitHistoryGraphSvg.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/right-sidebar/GitHistoryGraphSvg.tsx) |
| `GitHistoryPanel.test.tsx` | [`src/renderer/src/components/right-sidebar/GitHistoryPanel.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/right-sidebar/GitHistoryPanel.test.tsx) |
| `GitHistoryPanel.tsx` | [`src/renderer/src/components/right-sidebar/GitHistoryPanel.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/right-sidebar/GitHistoryPanel.tsx) |
| `GitHistoryRow.tsx` | [`src/renderer/src/components/right-sidebar/GitHistoryRow.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/right-sidebar/GitHistoryRow.tsx) |
| `HostedReviewActions.tsx` | [`src/renderer/src/components/right-sidebar/HostedReviewActions.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/right-sidebar/HostedReviewActions.tsx) |
| `HostedReviewStateActions.tsx` | [`src/renderer/src/components/right-sidebar/HostedReviewStateActions.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/right-sidebar/HostedReviewStateActions.tsx) |
| `PortsPanel.test.tsx` | [`src/renderer/src/components/right-sidebar/PortsPanel.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/right-sidebar/PortsPanel.test.tsx) |
| `PortsPanel.tsx` | [`src/renderer/src/components/right-sidebar/PortsPanel.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/right-sidebar/PortsPanel.tsx) |
| `PullRequestComposer.generate-tooltip.test.tsx` | [`src/renderer/src/components/right-sidebar/PullRequestComposer.generate-tooltip.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/right-sidebar/PullRequestComposer.generate-tooltip.test.tsx) |
| `Search.tsx` | [`src/renderer/src/components/right-sidebar/Search.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/right-sidebar/Search.tsx) |
| `SearchFilters.tsx` | [`src/renderer/src/components/right-sidebar/SearchFilters.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/right-sidebar/SearchFilters.tsx) |
| `SearchHeader.tsx` | [`src/renderer/src/components/right-sidebar/SearchHeader.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/right-sidebar/SearchHeader.tsx) |
| `SearchQueryRow.tsx` | [`src/renderer/src/components/right-sidebar/SearchQueryRow.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/right-sidebar/SearchQueryRow.tsx) |
| `SearchResultItems.test.tsx` | [`src/renderer/src/components/right-sidebar/SearchResultItems.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/right-sidebar/SearchResultItems.test.tsx) |
| `SearchResultItems.tsx` | [`src/renderer/src/components/right-sidebar/SearchResultItems.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/right-sidebar/SearchResultItems.tsx) |
| `SearchResultsPane.tsx` | [`src/renderer/src/components/right-sidebar/SearchResultsPane.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/right-sidebar/SearchResultsPane.tsx) |
| `SessionRowTrailingActions.tsx` | [`src/renderer/src/components/right-sidebar/SessionRowTrailingActions.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/right-sidebar/SessionRowTrailingActions.tsx) |
| `SourceControl.hosted-review-header-link.test.tsx` | [`src/renderer/src/components/right-sidebar/SourceControl.hosted-review-header-link.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/right-sidebar/SourceControl.hosted-review-header-link.test.tsx) |
| `SourceControl.open-file-highlight.test.tsx` | [`src/renderer/src/components/right-sidebar/SourceControl.open-file-highlight.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/right-sidebar/SourceControl.open-file-highlight.test.tsx) |
| `SourceControl.preview-open.test.tsx` | [`src/renderer/src/components/right-sidebar/SourceControl.preview-open.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/right-sidebar/SourceControl.preview-open.test.tsx) |
| `SourceControl.tsx` | [`src/renderer/src/components/right-sidebar/SourceControl.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/right-sidebar/SourceControl.tsx) |
| `SourceControlAgentActionDialog.test.tsx` | [`src/renderer/src/components/right-sidebar/SourceControlAgentActionDialog.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/right-sidebar/SourceControlAgentActionDialog.test.tsx) |
| `SourceControlAgentActionDialog.tsx` | [`src/renderer/src/components/right-sidebar/SourceControlAgentActionDialog.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/right-sidebar/SourceControlAgentActionDialog.tsx) |
| `SourceControlAgentActionDialogForm.test.tsx` | [`src/renderer/src/components/right-sidebar/SourceControlAgentActionDialogForm.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/right-sidebar/SourceControlAgentActionDialogForm.test.tsx) |
| `SourceControlAgentActionDialogForm.tsx` | [`src/renderer/src/components/right-sidebar/SourceControlAgentActionDialogForm.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/right-sidebar/SourceControlAgentActionDialogForm.tsx) |
| `SourceControlTextGenerationDialog.tsx` | [`src/renderer/src/components/right-sidebar/SourceControlTextGenerationDialog.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/right-sidebar/SourceControlTextGenerationDialog.tsx) |
| `SourceControlTextGenerationDialogForm.tsx` | [`src/renderer/src/components/right-sidebar/SourceControlTextGenerationDialogForm.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/right-sidebar/SourceControlTextGenerationDialogForm.tsx) |
| `activity-bar-buttons.tsx` | [`src/renderer/src/components/right-sidebar/activity-bar-buttons.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/right-sidebar/activity-bar-buttons.tsx) |
| `agent-session-history-icon.tsx` | [`src/renderer/src/components/right-sidebar/agent-session-history-icon.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/right-sidebar/agent-session-history-icon.tsx) |
| `check-job-log-tail.tsx` | [`src/renderer/src/components/right-sidebar/check-job-log-tail.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/right-sidebar/check-job-log-tail.tsx) |
| `checks-list-expanded-details.test.tsx` | [`src/renderer/src/components/right-sidebar/checks-list-expanded-details.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/right-sidebar/checks-list-expanded-details.test.tsx) |
| `checks-panel-content.test.tsx` | [`src/renderer/src/components/right-sidebar/checks-panel-content.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/right-sidebar/checks-panel-content.test.tsx) |
| `checks-panel-content.tsx` | [`src/renderer/src/components/right-sidebar/checks-panel-content.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/right-sidebar/checks-panel-content.tsx) |
| `checks-panel-updated-at-metadata.tsx` | [`src/renderer/src/components/right-sidebar/checks-panel-updated-at-metadata.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/right-sidebar/checks-panel-updated-at-metadata.tsx) |
| `file-explorer-drag-scroll-marker.test.tsx` | [`src/renderer/src/components/right-sidebar/file-explorer-drag-scroll-marker.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/right-sidebar/file-explorer-drag-scroll-marker.test.tsx) |
| `hosted-review-header-chrome.tsx` | [`src/renderer/src/components/right-sidebar/hosted-review-header-chrome.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/right-sidebar/hosted-review-header-chrome.tsx) |
| `index.tsx` | [`src/renderer/src/components/right-sidebar/index.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/right-sidebar/index.tsx) |
| `pr-comments-list-selection.test.tsx` | [`src/renderer/src/components/right-sidebar/pr-comments-list-selection.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/right-sidebar/pr-comments-list-selection.test.tsx) |
| `right-panel-comment-composer.tsx` | [`src/renderer/src/components/right-sidebar/right-panel-comment-composer.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/right-sidebar/right-panel-comment-composer.tsx) |
| `right-sidebar-panel-content.tsx` | [`src/renderer/src/components/right-sidebar/right-sidebar-panel-content.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/right-sidebar/right-sidebar-panel-content.tsx) |
| `right-sidebar-titlebar-drag-regions.render.test.tsx` | [`src/renderer/src/components/right-sidebar/right-sidebar-titlebar-drag-regions.render.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/right-sidebar/right-sidebar-titlebar-drag-regions.render.test.tsx) |
| `source-control-branch-context-row.test.tsx` | [`src/renderer/src/components/right-sidebar/source-control-branch-context-row.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/right-sidebar/source-control-branch-context-row.test.tsx) |
| `source-control-branch-context-row.tsx` | [`src/renderer/src/components/right-sidebar/source-control-branch-context-row.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/right-sidebar/source-control-branch-context-row.tsx) |
| `source-control-discard-dialog.test.tsx` | [`src/renderer/src/components/right-sidebar/source-control-discard-dialog.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/right-sidebar/source-control-discard-dialog.test.tsx) |
| `source-control-discard-dialog.tsx` | [`src/renderer/src/components/right-sidebar/source-control-discard-dialog.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/right-sidebar/source-control-discard-dialog.tsx) |
| `source-control-entry-context-menu.tsx` | [`src/renderer/src/components/right-sidebar/source-control-entry-context-menu.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/right-sidebar/source-control-entry-context-menu.tsx) |
| `source-control-fix-split-button.tsx` | [`src/renderer/src/components/right-sidebar/source-control-fix-split-button.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/right-sidebar/source-control-fix-split-button.tsx) |
| `source-control-header-icon-button.tsx` | [`src/renderer/src/components/right-sidebar/source-control-header-icon-button.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/right-sidebar/source-control-header-icon-button.tsx) |
| `source-control-header-overflow-menu.tsx` | [`src/renderer/src/components/right-sidebar/source-control-header-overflow-menu.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/right-sidebar/source-control-header-overflow-menu.tsx) |
| `source-control-header-toolbar.tsx` | [`src/renderer/src/components/right-sidebar/source-control-header-toolbar.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/right-sidebar/source-control-header-toolbar.tsx) |
| `source-control-pull-policy-error-notice.tsx` | [`src/renderer/src/components/right-sidebar/source-control-pull-policy-error-notice.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/right-sidebar/source-control-pull-policy-error-notice.tsx) |
| `AddProjectFromFolderDialog.test.tsx` | [`src/renderer/src/components/sidebar/AddProjectFromFolderDialog.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/AddProjectFromFolderDialog.test.tsx) |
| `AddProjectFromFolderDialog.tsx` | [`src/renderer/src/components/sidebar/AddProjectFromFolderDialog.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/AddProjectFromFolderDialog.tsx) |
| `AddRepoCloneStep.tsx` | [`src/renderer/src/components/sidebar/AddRepoCloneStep.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/AddRepoCloneStep.tsx) |
| `AddRepoCreateKindCard.tsx` | [`src/renderer/src/components/sidebar/AddRepoCreateKindCard.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/AddRepoCreateKindCard.tsx) |
| `AddRepoCreateStep.test.tsx` | [`src/renderer/src/components/sidebar/AddRepoCreateStep.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/AddRepoCreateStep.test.tsx) |
| `AddRepoCreateStep.tsx` | [`src/renderer/src/components/sidebar/AddRepoCreateStep.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/AddRepoCreateStep.tsx) |
| `AddRepoDialog.tsx` | [`src/renderer/src/components/sidebar/AddRepoDialog.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/AddRepoDialog.tsx) |
| `AddRepoDialogChrome.tsx` | [`src/renderer/src/components/sidebar/AddRepoDialogChrome.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/AddRepoDialogChrome.tsx) |
| `AddRepoDialogStepContent.test.tsx` | [`src/renderer/src/components/sidebar/AddRepoDialogStepContent.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/AddRepoDialogStepContent.test.tsx) |
| `AddRepoDialogStepContent.tsx` | [`src/renderer/src/components/sidebar/AddRepoDialogStepContent.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/AddRepoDialogStepContent.tsx) |
| `AddRepoHostSelector.test.tsx` | [`src/renderer/src/components/sidebar/AddRepoHostSelector.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/AddRepoHostSelector.test.tsx) |
| `AddRepoHostSelector.tsx` | [`src/renderer/src/components/sidebar/AddRepoHostSelector.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/AddRepoHostSelector.tsx) |
| `AddRepoHostSelectorSlot.tsx` | [`src/renderer/src/components/sidebar/AddRepoHostSelectorSlot.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/AddRepoHostSelectorSlot.tsx) |
| `AddRepoNestedImportStep.test.tsx` | [`src/renderer/src/components/sidebar/AddRepoNestedImportStep.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/AddRepoNestedImportStep.test.tsx) |
| `AddRepoNestedImportStep.tsx` | [`src/renderer/src/components/sidebar/AddRepoNestedImportStep.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/AddRepoNestedImportStep.tsx) |
| `AddRepoRemoteStep.tsx` | [`src/renderer/src/components/sidebar/AddRepoRemoteStep.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/AddRepoRemoteStep.tsx) |
| `AddRepoServerStartStep.tsx` | [`src/renderer/src/components/sidebar/AddRepoServerStartStep.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/AddRepoServerStartStep.tsx) |
| `AddRepoStartSteps.test.tsx` | [`src/renderer/src/components/sidebar/AddRepoStartSteps.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/AddRepoStartSteps.test.tsx) |
| `AddRepoStartSteps.tsx` | [`src/renderer/src/components/sidebar/AddRepoStartSteps.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/AddRepoStartSteps.tsx) |
| `AddRepoStepIndicator.tsx` | [`src/renderer/src/components/sidebar/AddRepoStepIndicator.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/AddRepoStepIndicator.tsx) |
| `AddRepoSteps.tsx` | [`src/renderer/src/components/sidebar/AddRepoSteps.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/AddRepoSteps.tsx) |
| `AutoRenameFailedDialog.tsx` | [`src/renderer/src/components/sidebar/AutoRenameFailedDialog.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/AutoRenameFailedDialog.tsx) |
| `CacheTimer.test.tsx` | [`src/renderer/src/components/sidebar/CacheTimer.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/CacheTimer.test.tsx) |
| `CacheTimer.tsx` | [`src/renderer/src/components/sidebar/CacheTimer.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/CacheTimer.tsx) |
| `CommentMarkdown.test.tsx` | [`src/renderer/src/components/sidebar/CommentMarkdown.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/CommentMarkdown.test.tsx) |
| `CommentMarkdown.tsx` | [`src/renderer/src/components/sidebar/CommentMarkdown.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/CommentMarkdown.tsx) |
| `CommentMermaidBlock.tsx` | [`src/renderer/src/components/sidebar/CommentMermaidBlock.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/CommentMermaidBlock.tsx) |
| `CreateProjectLocationField.tsx` | [`src/renderer/src/components/sidebar/CreateProjectLocationField.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/CreateProjectLocationField.tsx) |
| `DeleteWorktreeDialog.test.tsx` | [`src/renderer/src/components/sidebar/DeleteWorktreeDialog.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/DeleteWorktreeDialog.test.tsx) |
| `DeleteWorktreeDialog.tsx` | [`src/renderer/src/components/sidebar/DeleteWorktreeDialog.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/DeleteWorktreeDialog.tsx) |
| `DeleteWorktreeDialogDescription.tsx` | [`src/renderer/src/components/sidebar/DeleteWorktreeDialogDescription.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/DeleteWorktreeDialogDescription.tsx) |
| `DeleteWorktreeDialogFooter.tsx` | [`src/renderer/src/components/sidebar/DeleteWorktreeDialogFooter.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/DeleteWorktreeDialogFooter.tsx) |
| `DeleteWorktreeDirtyChangeHint.tsx` | [`src/renderer/src/components/sidebar/DeleteWorktreeDirtyChangeHint.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/DeleteWorktreeDirtyChangeHint.tsx) |
| `DeleteWorktreeLineageNotice.tsx` | [`src/renderer/src/components/sidebar/DeleteWorktreeLineageNotice.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/DeleteWorktreeLineageNotice.tsx) |
| `DeleteWorktreeSkipConfirmOption.tsx` | [`src/renderer/src/components/sidebar/DeleteWorktreeSkipConfirmOption.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/DeleteWorktreeSkipConfirmOption.tsx) |
| `DeleteWorktreeTargetPreview.tsx` | [`src/renderer/src/components/sidebar/DeleteWorktreeTargetPreview.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/DeleteWorktreeTargetPreview.tsx) |
| `DeleteWorktreeWarningPanels.tsx` | [`src/renderer/src/components/sidebar/DeleteWorktreeWarningPanels.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/DeleteWorktreeWarningPanels.tsx) |
| `HostRemoveDialog.tsx` | [`src/renderer/src/components/sidebar/HostRemoveDialog.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/HostRemoveDialog.tsx) |
| `HostRenameDialog.tsx` | [`src/renderer/src/components/sidebar/HostRenameDialog.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/HostRenameDialog.tsx) |
| `HostSectionHeaderMenu.tsx` | [`src/renderer/src/components/sidebar/HostSectionHeaderMenu.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/HostSectionHeaderMenu.tsx) |
| `ImportedWorktreesVisibilityLine.test.tsx` | [`src/renderer/src/components/sidebar/ImportedWorktreesVisibilityLine.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/ImportedWorktreesVisibilityLine.test.tsx) |
| `ImportedWorktreesVisibilityLine.tsx` | [`src/renderer/src/components/sidebar/ImportedWorktreesVisibilityLine.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/ImportedWorktreesVisibilityLine.tsx) |
| `LinearAgentSkillSetupDialog.tsx` | [`src/renderer/src/components/sidebar/LinearAgentSkillSetupDialog.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/LinearAgentSkillSetupDialog.tsx) |
| `LinearAgentSkillSetupPrompt.reminder-toast.test.tsx` | [`src/renderer/src/components/sidebar/LinearAgentSkillSetupPrompt.reminder-toast.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/LinearAgentSkillSetupPrompt.reminder-toast.test.tsx) |
| `LinearAgentSkillSetupPrompt.test.tsx` | [`src/renderer/src/components/sidebar/LinearAgentSkillSetupPrompt.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/LinearAgentSkillSetupPrompt.test.tsx) |
| `LinearAgentSkillSetupPrompt.tsx` | [`src/renderer/src/components/sidebar/LinearAgentSkillSetupPrompt.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/LinearAgentSkillSetupPrompt.tsx) |
| `LinearAgentSkillSetupPrompt.update-command.test.tsx` | [`src/renderer/src/components/sidebar/LinearAgentSkillSetupPrompt.update-command.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/LinearAgentSkillSetupPrompt.update-command.test.tsx) |
| `NonGitFolderDialog.tsx` | [`src/renderer/src/components/sidebar/NonGitFolderDialog.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/NonGitFolderDialog.tsx) |
| `OrcaYamlTrustDialog.tsx` | [`src/renderer/src/components/sidebar/OrcaYamlTrustDialog.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/OrcaYamlTrustDialog.tsx) |
| `PendingWorktreeRow.tsx` | [`src/renderer/src/components/sidebar/PendingWorktreeRow.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/PendingWorktreeRow.tsx) |
| `ProjectAddedDialog.test.tsx` | [`src/renderer/src/components/sidebar/ProjectAddedDialog.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/ProjectAddedDialog.test.tsx) |
| `ProjectAddedDialog.tsx` | [`src/renderer/src/components/sidebar/ProjectAddedDialog.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/ProjectAddedDialog.tsx) |
| `ProjectGroupDeleteDialog.test.tsx` | [`src/renderer/src/components/sidebar/ProjectGroupDeleteDialog.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/ProjectGroupDeleteDialog.test.tsx) |
| `ProjectGroupDeleteDialog.tsx` | [`src/renderer/src/components/sidebar/ProjectGroupDeleteDialog.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/ProjectGroupDeleteDialog.tsx) |
| `ProjectGroupNameDialog.tsx` | [`src/renderer/src/components/sidebar/ProjectGroupNameDialog.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/ProjectGroupNameDialog.tsx) |
| `ProjectHeaderActions.test.tsx` | [`src/renderer/src/components/sidebar/ProjectHeaderActions.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/ProjectHeaderActions.test.tsx) |
| `ProjectHeaderActions.tsx` | [`src/renderer/src/components/sidebar/ProjectHeaderActions.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/ProjectHeaderActions.tsx) |
| `ProjectOrderManualDefaultNotice.tsx` | [`src/renderer/src/components/sidebar/ProjectOrderManualDefaultNotice.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/ProjectOrderManualDefaultNotice.tsx) |
| `RemoteFileBrowser.paste.test.tsx` | [`src/renderer/src/components/sidebar/RemoteFileBrowser.paste.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/RemoteFileBrowser.paste.test.tsx) |
| `RemoteFileBrowser.tsx` | [`src/renderer/src/components/sidebar/RemoteFileBrowser.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/RemoteFileBrowser.tsx) |
| `RemoveFolderDialog.tsx` | [`src/renderer/src/components/sidebar/RemoveFolderDialog.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/RemoveFolderDialog.tsx) |
| `ScrollToCurrentWorkspaceToolbarButton.tsx` | [`src/renderer/src/components/sidebar/ScrollToCurrentWorkspaceToolbarButton.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/ScrollToCurrentWorkspaceToolbarButton.tsx) |
| `SetupGuideSidebarEntry.test.tsx` | [`src/renderer/src/components/sidebar/SetupGuideSidebarEntry.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/SetupGuideSidebarEntry.test.tsx) |
| `SetupGuideSidebarEntry.tsx` | [`src/renderer/src/components/sidebar/SetupGuideSidebarEntry.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/SetupGuideSidebarEntry.tsx) |
| `SetupScriptPromptCard.tsx` | [`src/renderer/src/components/sidebar/SetupScriptPromptCard.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/SetupScriptPromptCard.tsx) |
| `SetupScriptPromptCardShell.tsx` | [`src/renderer/src/components/sidebar/SetupScriptPromptCardShell.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/SetupScriptPromptCardShell.tsx) |
| `SetupScriptPromptCardViews.tsx` | [`src/renderer/src/components/sidebar/SetupScriptPromptCardViews.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/SetupScriptPromptCardViews.tsx) |
| `SetupScriptPromptToast.tsx` | [`src/renderer/src/components/sidebar/SetupScriptPromptToast.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/SetupScriptPromptToast.tsx) |
| `Sidebar.test.tsx` | [`src/renderer/src/components/sidebar/Sidebar.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/Sidebar.test.tsx) |
| `SidebarFeedbackDialog.tsx` | [`src/renderer/src/components/sidebar/SidebarFeedbackDialog.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/SidebarFeedbackDialog.tsx) |
| `SidebarFilter.tsx` | [`src/renderer/src/components/sidebar/SidebarFilter.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/SidebarFilter.tsx) |
| `SidebarGroupByToggle.test.tsx` | [`src/renderer/src/components/sidebar/SidebarGroupByToggle.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/SidebarGroupByToggle.test.tsx) |
| `SidebarGroupByToggle.tsx` | [`src/renderer/src/components/sidebar/SidebarGroupByToggle.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/SidebarGroupByToggle.tsx) |
| `SidebarHeader.tsx` | [`src/renderer/src/components/sidebar/SidebarHeader.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/SidebarHeader.tsx) |
| `SidebarHostScopeMenuSection.tsx` | [`src/renderer/src/components/sidebar/SidebarHostScopeMenuSection.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/SidebarHostScopeMenuSection.tsx) |
| `SidebarHostScopeStrip.tsx` | [`src/renderer/src/components/sidebar/SidebarHostScopeStrip.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/SidebarHostScopeStrip.tsx) |
| `SidebarNav.test.tsx` | [`src/renderer/src/components/sidebar/SidebarNav.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/SidebarNav.test.tsx) |
| `SidebarNav.tsx` | [`src/renderer/src/components/sidebar/SidebarNav.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/SidebarNav.tsx) |
| `SidebarRepositoryFilterSection.tsx` | [`src/renderer/src/components/sidebar/SidebarRepositoryFilterSection.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/SidebarRepositoryFilterSection.tsx) |
| `SidebarSettingsHelpMenu.test.tsx` | [`src/renderer/src/components/sidebar/SidebarSettingsHelpMenu.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/SidebarSettingsHelpMenu.test.tsx) |
| `SidebarSettingsHelpMenu.tsx` | [`src/renderer/src/components/sidebar/SidebarSettingsHelpMenu.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/SidebarSettingsHelpMenu.tsx) |
| `SidebarTaskNavButton.tsx` | [`src/renderer/src/components/sidebar/SidebarTaskNavButton.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/SidebarTaskNavButton.tsx) |
| `SidebarToolbar.test.tsx` | [`src/renderer/src/components/sidebar/SidebarToolbar.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/SidebarToolbar.test.tsx) |
| `SidebarToolbar.tsx` | [`src/renderer/src/components/sidebar/SidebarToolbar.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/SidebarToolbar.tsx) |
| `SidebarWorkspaceFilterSection.tsx` | [`src/renderer/src/components/sidebar/SidebarWorkspaceFilterSection.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/SidebarWorkspaceFilterSection.tsx) |
| `SidebarWorkspaceOptionsMenu.tsx` | [`src/renderer/src/components/sidebar/SidebarWorkspaceOptionsMenu.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/SidebarWorkspaceOptionsMenu.tsx) |
| `SshDisconnectedDialog.tsx` | [`src/renderer/src/components/sidebar/SshDisconnectedDialog.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/SshDisconnectedDialog.tsx) |
| `SshTargetRow.tsx` | [`src/renderer/src/components/sidebar/SshTargetRow.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/SshTargetRow.tsx) |
| `StatusIndicator.tsx` | [`src/renderer/src/components/sidebar/StatusIndicator.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/StatusIndicator.tsx) |
| `WorkspaceKanbanAreaSelectionOverlay.tsx` | [`src/renderer/src/components/sidebar/WorkspaceKanbanAreaSelectionOverlay.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/WorkspaceKanbanAreaSelectionOverlay.tsx) |
| `WorkspaceKanbanCard.tsx` | [`src/renderer/src/components/sidebar/WorkspaceKanbanCard.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/WorkspaceKanbanCard.tsx) |
| `WorkspaceKanbanDrawer.task-status-sync.test.tsx` | [`src/renderer/src/components/sidebar/WorkspaceKanbanDrawer.task-status-sync.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/WorkspaceKanbanDrawer.task-status-sync.test.tsx) |
| `WorkspaceKanbanDrawer.tsx` | [`src/renderer/src/components/sidebar/WorkspaceKanbanDrawer.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/WorkspaceKanbanDrawer.tsx) |
| `WorkspaceKanbanDrawerHeader.test.tsx` | [`src/renderer/src/components/sidebar/WorkspaceKanbanDrawerHeader.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/WorkspaceKanbanDrawerHeader.test.tsx) |
| `WorkspaceKanbanDrawerHeader.tsx` | [`src/renderer/src/components/sidebar/WorkspaceKanbanDrawerHeader.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/WorkspaceKanbanDrawerHeader.tsx) |
| `WorkspaceKanbanLaneGrid.tsx` | [`src/renderer/src/components/sidebar/WorkspaceKanbanLaneGrid.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/WorkspaceKanbanLaneGrid.tsx) |
| `WorkspaceKanbanPinDropTarget.tsx` | [`src/renderer/src/components/sidebar/WorkspaceKanbanPinDropTarget.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/WorkspaceKanbanPinDropTarget.tsx) |
| `WorkspaceKanbanSettingsMenu.test.tsx` | [`src/renderer/src/components/sidebar/WorkspaceKanbanSettingsMenu.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/WorkspaceKanbanSettingsMenu.test.tsx) |
| `WorkspaceKanbanSettingsMenu.tsx` | [`src/renderer/src/components/sidebar/WorkspaceKanbanSettingsMenu.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/WorkspaceKanbanSettingsMenu.tsx) |
| `WorkspaceKanbanStatusLane.tsx` | [`src/renderer/src/components/sidebar/WorkspaceKanbanStatusLane.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/WorkspaceKanbanStatusLane.tsx) |
| `WorkspaceStatusAppearancePopover.tsx` | [`src/renderer/src/components/sidebar/WorkspaceStatusAppearancePopover.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/WorkspaceStatusAppearancePopover.tsx) |
| `WorktreeActivityStatusIndicator.test.tsx` | [`src/renderer/src/components/sidebar/WorktreeActivityStatusIndicator.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/WorktreeActivityStatusIndicator.test.tsx) |
| `WorktreeActivityStatusIndicator.tsx` | [`src/renderer/src/components/sidebar/WorktreeActivityStatusIndicator.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/WorktreeActivityStatusIndicator.tsx) |
| `WorktreeCard.affiliate-list-mode.test.tsx` | [`src/renderer/src/components/sidebar/WorktreeCard.affiliate-list-mode.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/WorktreeCard.affiliate-list-mode.test.tsx) |
| `WorktreeCard.compact-hover.test.tsx` | [`src/renderer/src/components/sidebar/WorktreeCard.compact-hover.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/WorktreeCard.compact-hover.test.tsx) |
| `WorktreeCard.hosted-review-refresh.test.tsx` | [`src/renderer/src/components/sidebar/WorktreeCard.hosted-review-refresh.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/WorktreeCard.hosted-review-refresh.test.tsx) |
| `WorktreeCard.lineage.test.tsx` | [`src/renderer/src/components/sidebar/WorktreeCard.lineage.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/WorktreeCard.lineage.test.tsx) |
| `WorktreeCard.pinned-repo-icon.test.tsx` | [`src/renderer/src/components/sidebar/WorktreeCard.pinned-repo-icon.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/WorktreeCard.pinned-repo-icon.test.tsx) |
| `WorktreeCard.pr-display.test.tsx` | [`src/renderer/src/components/sidebar/WorktreeCard.pr-display.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/WorktreeCard.pr-display.test.tsx) |
| `WorktreeCard.quick-actions.test.tsx` | [`src/renderer/src/components/sidebar/WorktreeCard.quick-actions.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/WorktreeCard.quick-actions.test.tsx) |
| `WorktreeCard.ssh-reconnect-prompt.test.tsx` | [`src/renderer/src/components/sidebar/WorktreeCard.ssh-reconnect-prompt.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/WorktreeCard.ssh-reconnect-prompt.test.tsx) |
| `WorktreeCard.tsx` | [`src/renderer/src/components/sidebar/WorktreeCard.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/WorktreeCard.tsx) |
| `WorktreeCardAgents.send-target.test.tsx` | [`src/renderer/src/components/sidebar/WorktreeCardAgents.send-target.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/WorktreeCardAgents.send-target.test.tsx) |
| `WorktreeCardAgents.test.tsx` | [`src/renderer/src/components/sidebar/WorktreeCardAgents.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/WorktreeCardAgents.test.tsx) |
| `WorktreeCardAgents.tsx` | [`src/renderer/src/components/sidebar/WorktreeCardAgents.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/WorktreeCardAgents.tsx) |
| `WorktreeCardAutomationDetailSection.tsx` | [`src/renderer/src/components/sidebar/WorktreeCardAutomationDetailSection.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/WorktreeCardAutomationDetailSection.tsx) |
| `WorktreeCardDetailSection.tsx` | [`src/renderer/src/components/sidebar/WorktreeCardDetailSection.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/WorktreeCardDetailSection.tsx) |
| `WorktreeCardDisplayMenuSection.test.tsx` | [`src/renderer/src/components/sidebar/WorktreeCardDisplayMenuSection.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/WorktreeCardDisplayMenuSection.test.tsx) |
| `WorktreeCardDisplayMenuSection.tsx` | [`src/renderer/src/components/sidebar/WorktreeCardDisplayMenuSection.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/WorktreeCardDisplayMenuSection.tsx) |
| `WorktreeCardHelpers.tsx` | [`src/renderer/src/components/sidebar/WorktreeCardHelpers.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/WorktreeCardHelpers.tsx) |
| `WorktreeCardIssueDetailSection.tsx` | [`src/renderer/src/components/sidebar/WorktreeCardIssueDetailSection.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/WorktreeCardIssueDetailSection.tsx) |
| `WorktreeCardMeta.interaction.test.tsx` | [`src/renderer/src/components/sidebar/WorktreeCardMeta.interaction.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/WorktreeCardMeta.interaction.test.tsx) |
| `WorktreeCardMeta.test.tsx` | [`src/renderer/src/components/sidebar/WorktreeCardMeta.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/WorktreeCardMeta.test.tsx) |
| `WorktreeCardMeta.tsx` | [`src/renderer/src/components/sidebar/WorktreeCardMeta.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/WorktreeCardMeta.tsx) |
| `WorktreeCardMetadataControls.tsx` | [`src/renderer/src/components/sidebar/WorktreeCardMetadataControls.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/WorktreeCardMetadataControls.tsx) |
| `WorktreeCardMetadataStatusBadges.tsx` | [`src/renderer/src/components/sidebar/WorktreeCardMetadataStatusBadges.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/WorktreeCardMetadataStatusBadges.tsx) |
| `WorktreeCardPorts.test.tsx` | [`src/renderer/src/components/sidebar/WorktreeCardPorts.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/WorktreeCardPorts.test.tsx) |
| `WorktreeCardPorts.tsx` | [`src/renderer/src/components/sidebar/WorktreeCardPorts.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/WorktreeCardPorts.tsx) |
| `WorktreeCardReviewDetailSection.tsx` | [`src/renderer/src/components/sidebar/WorktreeCardReviewDetailSection.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/WorktreeCardReviewDetailSection.tsx) |
| `WorktreeCardStatusSlot.test.tsx` | [`src/renderer/src/components/sidebar/WorktreeCardStatusSlot.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/WorktreeCardStatusSlot.test.tsx) |
| `WorktreeCardStatusSlot.tsx` | [`src/renderer/src/components/sidebar/WorktreeCardStatusSlot.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/WorktreeCardStatusSlot.tsx) |
| `WorktreeContextMenu.tsx` | [`src/renderer/src/components/sidebar/WorktreeContextMenu.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/WorktreeContextMenu.tsx) |
| `WorktreeList.lineage-child-real-card.test.tsx` | [`src/renderer/src/components/sidebar/WorktreeList.lineage-child-real-card.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/WorktreeList.lineage-child-real-card.test.tsx) |
| `WorktreeList.tsx` | [`src/renderer/src/components/sidebar/WorktreeList.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/WorktreeList.tsx) |
| `WorktreeMetaDialog.tsx` | [`src/renderer/src/components/sidebar/WorktreeMetaDialog.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/WorktreeMetaDialog.tsx) |
| `WorktreeOpenInMenu.test.tsx` | [`src/renderer/src/components/sidebar/WorktreeOpenInMenu.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/WorktreeOpenInMenu.test.tsx) |
| `WorktreeOpenInMenu.tsx` | [`src/renderer/src/components/sidebar/WorktreeOpenInMenu.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/WorktreeOpenInMenu.tsx) |
| `WorktreeParentPickerPopover.tsx` | [`src/renderer/src/components/sidebar/WorktreeParentPickerPopover.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/WorktreeParentPickerPopover.tsx) |
| `WorktreeTitleInlineRename.begin-editing.test.tsx` | [`src/renderer/src/components/sidebar/WorktreeTitleInlineRename.begin-editing.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/WorktreeTitleInlineRename.begin-editing.test.tsx) |
| `WorktreeTitleInlineRename.test.tsx` | [`src/renderer/src/components/sidebar/WorktreeTitleInlineRename.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/WorktreeTitleInlineRename.test.tsx) |
| `WorktreeTitleInlineRename.tsx` | [`src/renderer/src/components/sidebar/WorktreeTitleInlineRename.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/WorktreeTitleInlineRename.tsx) |
| `WorktreeVisibilityDialog.tsx` | [`src/renderer/src/components/sidebar/WorktreeVisibilityDialog.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/WorktreeVisibilityDialog.tsx) |
| `comment-mermaid-fence.tsx` | [`src/renderer/src/components/sidebar/comment-mermaid-fence.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/comment-mermaid-fence.tsx) |
| `folder-workspace-composer-path-status.test.tsx` | [`src/renderer/src/components/sidebar/folder-workspace-composer-path-status.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/folder-workspace-composer-path-status.test.tsx) |
| `index.tsx` | [`src/renderer/src/components/sidebar/index.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/index.tsx) |
| `local-base-ref-suggestion-toast.test.tsx` | [`src/renderer/src/components/sidebar/local-base-ref-suggestion-toast.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/local-base-ref-suggestion-toast.test.tsx) |
| `local-base-ref-suggestion-toast.tsx` | [`src/renderer/src/components/sidebar/local-base-ref-suggestion-toast.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/local-base-ref-suggestion-toast.tsx) |
| `preserved-branch-toast.test.tsx` | [`src/renderer/src/components/sidebar/preserved-branch-toast.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/preserved-branch-toast.test.tsx) |
| `preserved-branch-toast.tsx` | [`src/renderer/src/components/sidebar/preserved-branch-toast.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/preserved-branch-toast.tsx) |
| `sidebar-nav-controls.tsx` | [`src/renderer/src/components/sidebar/sidebar-nav-controls.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/sidebar-nav-controls.tsx) |
| `truncated-sidebar-label.test.tsx` | [`src/renderer/src/components/sidebar/truncated-sidebar-label.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/truncated-sidebar-label.test.tsx) |
| `truncated-sidebar-label.tsx` | [`src/renderer/src/components/sidebar/truncated-sidebar-label.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/truncated-sidebar-label.tsx) |
| `use-worktree-activity-status.test.tsx` | [`src/renderer/src/components/sidebar/use-worktree-activity-status.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/use-worktree-activity-status.test.tsx) |
| `useWorkspaceBoardPanel.test.tsx` | [`src/renderer/src/components/sidebar/useWorkspaceBoardPanel.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/useWorkspaceBoardPanel.test.tsx) |
| `workspace-status-icons.tsx` | [`src/renderer/src/components/sidebar/workspace-status-icons.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/workspace-status-icons.tsx) |
| `worktree-card-compact-agent-row.tsx` | [`src/renderer/src/components/sidebar/worktree-card-compact-agent-row.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/worktree-card-compact-agent-row.tsx) |
| `worktree-card-compact-agents.tsx` | [`src/renderer/src/components/sidebar/worktree-card-compact-agents.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/worktree-card-compact-agents.tsx) |
| `worktree-card-details-hover-state.test.tsx` | [`src/renderer/src/components/sidebar/worktree-card-details-hover-state.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/worktree-card-details-hover-state.test.tsx) |
| `worktree-review-helpers.test.tsx` | [`src/renderer/src/components/sidebar/worktree-review-helpers.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/worktree-review-helpers.test.tsx) |
| `worktree-review-helpers.tsx` | [`src/renderer/src/components/sidebar/worktree-review-helpers.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/sidebar/worktree-review-helpers.tsx) |
| `BrowserTab.test.tsx` | [`src/renderer/src/components/tab-bar/BrowserTab.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/tab-bar/BrowserTab.test.tsx) |
| `BrowserTab.tsx` | [`src/renderer/src/components/tab-bar/BrowserTab.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/tab-bar/BrowserTab.tsx) |
| `EditorFileTab.test.tsx` | [`src/renderer/src/components/tab-bar/EditorFileTab.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/tab-bar/EditorFileTab.test.tsx) |
| `EditorFileTab.tsx` | [`src/renderer/src/components/tab-bar/EditorFileTab.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/tab-bar/EditorFileTab.tsx) |
| `EditorFileTabCloseButton.tsx` | [`src/renderer/src/components/tab-bar/EditorFileTabCloseButton.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/tab-bar/EditorFileTabCloseButton.tsx) |
| `EditorFileTabContextMenu.test.tsx` | [`src/renderer/src/components/tab-bar/EditorFileTabContextMenu.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/tab-bar/EditorFileTabContextMenu.test.tsx) |
| `EditorFileTabContextMenu.tsx` | [`src/renderer/src/components/tab-bar/EditorFileTabContextMenu.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/tab-bar/EditorFileTabContextMenu.tsx) |
| `QuickLaunchButton.tsx` | [`src/renderer/src/components/tab-bar/QuickLaunchButton.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/tab-bar/QuickLaunchButton.tsx) |
| `RecentTabSwitcher.test.tsx` | [`src/renderer/src/components/tab-bar/RecentTabSwitcher.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/tab-bar/RecentTabSwitcher.test.tsx) |
| `RecentTabSwitcher.tsx` | [`src/renderer/src/components/tab-bar/RecentTabSwitcher.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/tab-bar/RecentTabSwitcher.tsx) |
| `SortableTab.rename-shortcut.test.tsx` | [`src/renderer/src/components/tab-bar/SortableTab.rename-shortcut.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/tab-bar/SortableTab.rename-shortcut.test.tsx) |
| `SortableTab.tsx` | [`src/renderer/src/components/tab-bar/SortableTab.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/tab-bar/SortableTab.tsx) |
| `SortableTabContextMenu.test.tsx` | [`src/renderer/src/components/tab-bar/SortableTabContextMenu.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/tab-bar/SortableTabContextMenu.test.tsx) |
| `SortableTabContextMenu.tsx` | [`src/renderer/src/components/tab-bar/SortableTabContextMenu.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/tab-bar/SortableTabContextMenu.tsx) |
| `TabBar.tsx` | [`src/renderer/src/components/tab-bar/TabBar.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/tab-bar/TabBar.tsx) |
| `TabBarCreateEntry.keyboard.test.tsx` | [`src/renderer/src/components/tab-bar/TabBarCreateEntry.keyboard.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/tab-bar/TabBarCreateEntry.keyboard.test.tsx) |
| `TabBarCreateEntry.tsx` | [`src/renderer/src/components/tab-bar/TabBarCreateEntry.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/tab-bar/TabBarCreateEntry.tsx) |
| `TabBarCreateEntryRow.tsx` | [`src/renderer/src/components/tab-bar/TabBarCreateEntryRow.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/tab-bar/TabBarCreateEntryRow.tsx) |
| `TabBarQuickCommandsButton.tsx` | [`src/renderer/src/components/tab-bar/TabBarQuickCommandsButton.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/tab-bar/TabBarQuickCommandsButton.tsx) |
| `TabBarQuickCommandsMenu.tsx` | [`src/renderer/src/components/tab-bar/TabBarQuickCommandsMenu.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/tab-bar/TabBarQuickCommandsMenu.tsx) |
| `TabDragPreview.tsx` | [`src/renderer/src/components/tab-bar/TabDragPreview.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/tab-bar/TabDragPreview.tsx) |
| `TabStripScrollIndicator.tsx` | [`src/renderer/src/components/tab-bar/TabStripScrollIndicator.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/tab-bar/TabStripScrollIndicator.tsx) |
| `TabWorkspaceLayoutMenuSection.tsx` | [`src/renderer/src/components/tab-bar/TabWorkspaceLayoutMenuSection.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/tab-bar/TabWorkspaceLayoutMenuSection.tsx) |
| `shell-icons.tsx` | [`src/renderer/src/components/tab-bar/shell-icons.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/tab-bar/shell-icons.tsx) |
| `tab-strip-pointer-activation.test.tsx` | [`src/renderer/src/components/tab-bar/tab-strip-pointer-activation.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/tab-bar/tab-strip-pointer-activation.test.tsx) |
| `tab-title-tooltip.test.tsx` | [`src/renderer/src/components/tab-bar/tab-title-tooltip.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/tab-bar/tab-title-tooltip.test.tsx) |
| `AiVaultSessionDropLayer.tsx` | [`src/renderer/src/components/tab-group/AiVaultSessionDropLayer.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/tab-group/AiVaultSessionDropLayer.tsx) |
| `TabGroupDropOverlay.tsx` | [`src/renderer/src/components/tab-group/TabGroupDropOverlay.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/tab-group/TabGroupDropOverlay.tsx) |
| `TabGroupPanel.tsx` | [`src/renderer/src/components/tab-group/TabGroupPanel.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/tab-group/TabGroupPanel.tsx) |
| `TabGroupSplitLayout.tsx` | [`src/renderer/src/components/tab-group/TabGroupSplitLayout.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/tab-group/TabGroupSplitLayout.tsx) |
| `TabPaneColumnSplitDragOverlay.test.tsx` | [`src/renderer/src/components/tab-group/TabPaneColumnSplitDragOverlay.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/tab-group/TabPaneColumnSplitDragOverlay.test.tsx) |
| `TabPaneColumnSplitDragOverlay.tsx` | [`src/renderer/src/components/tab-group/TabPaneColumnSplitDragOverlay.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/tab-group/TabPaneColumnSplitDragOverlay.tsx) |
| `tab-drag-context.tsx` | [`src/renderer/src/components/tab-group/tab-drag-context.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/tab-group/tab-drag-context.tsx) |

## Desktop App - Status Bar & System Monitoring

*Total: 20 arquivos*

| Arquivo | Caminho Completo |
| :--- | :--- |
| `PetOverlay.tsx` | [`src/renderer/src/components/pet/PetOverlay.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/pet/PetOverlay.tsx) |
| `WorkspacePortScanner.test.tsx` | [`src/renderer/src/components/ports/WorkspacePortScanner.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/ports/WorkspacePortScanner.test.tsx) |
| `WorkspacePortScanner.tsx` | [`src/renderer/src/components/ports/WorkspacePortScanner.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/ports/WorkspacePortScanner.tsx) |
| `PetStatusSegment.tsx` | [`src/renderer/src/components/status-bar/PetStatusSegment.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/status-bar/PetStatusSegment.tsx) |
| `PortsStatusSegment.tsx` | [`src/renderer/src/components/status-bar/PortsStatusSegment.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/status-bar/PortsStatusSegment.tsx) |
| `ResourceUsageStatusSegment.tsx` | [`src/renderer/src/components/status-bar/ResourceUsageStatusSegment.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/status-bar/ResourceUsageStatusSegment.tsx) |
| `RuntimeHostStatusRow.test.tsx` | [`src/renderer/src/components/status-bar/RuntimeHostStatusRow.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/status-bar/RuntimeHostStatusRow.test.tsx) |
| `RuntimeHostStatusRow.tsx` | [`src/renderer/src/components/status-bar/RuntimeHostStatusRow.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/status-bar/RuntimeHostStatusRow.tsx) |
| `SshStatusSegment.tsx` | [`src/renderer/src/components/status-bar/SshStatusSegment.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/status-bar/SshStatusSegment.tsx) |
| `SshTargetStatusRow.tsx` | [`src/renderer/src/components/status-bar/SshTargetStatusRow.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/status-bar/SshTargetStatusRow.tsx) |
| `StatusBar.tsx` | [`src/renderer/src/components/status-bar/StatusBar.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/status-bar/StatusBar.tsx) |
| `StatusBarUsageEmptyCta.tsx` | [`src/renderer/src/components/status-bar/StatusBarUsageEmptyCta.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/status-bar/StatusBarUsageEmptyCta.tsx) |
| `UpdateStatusSegment.tsx` | [`src/renderer/src/components/status-bar/UpdateStatusSegment.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/status-bar/UpdateStatusSegment.tsx) |
| `WorkspaceSpaceCompactPanel.tsx` | [`src/renderer/src/components/status-bar/WorkspaceSpaceCompactPanel.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/status-bar/WorkspaceSpaceCompactPanel.tsx) |
| `WorkspaceSpaceManagerPanel.tsx` | [`src/renderer/src/components/status-bar/WorkspaceSpaceManagerPanel.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/status-bar/WorkspaceSpaceManagerPanel.tsx) |
| `icons.tsx` | [`src/renderer/src/components/status-bar/icons.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/status-bar/icons.tsx) |
| `ports-status-popover-rows.test.tsx` | [`src/renderer/src/components/status-bar/ports-status-popover-rows.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/status-bar/ports-status-popover-rows.test.tsx) |
| `ports-status-popover-rows.tsx` | [`src/renderer/src/components/status-bar/ports-status-popover-rows.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/status-bar/ports-status-popover-rows.tsx) |
| `status-bar-provider-menu-focus.test.tsx` | [`src/renderer/src/components/status-bar/status-bar-provider-menu-focus.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/status-bar/status-bar-provider-menu-focus.test.tsx) |
| `tooltip.tsx` | [`src/renderer/src/components/status-bar/tooltip.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/status-bar/tooltip.tsx) |

## Desktop App - Settings & Configuration

*Total: 205 arquivos*

| Arquivo | Caminho Completo |
| :--- | :--- |
| `AccountsPane.test.tsx` | [`src/renderer/src/components/settings/AccountsPane.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/AccountsPane.test.tsx) |
| `AccountsPane.tsx` | [`src/renderer/src/components/settings/AccountsPane.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/AccountsPane.tsx) |
| `AdvancedNetworkSettingsSection.tsx` | [`src/renderer/src/components/settings/AdvancedNetworkSettingsSection.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/AdvancedNetworkSettingsSection.tsx) |
| `AdvancedPane.test.tsx` | [`src/renderer/src/components/settings/AdvancedPane.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/AdvancedPane.test.tsx) |
| `AdvancedPane.tsx` | [`src/renderer/src/components/settings/AdvancedPane.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/AdvancedPane.tsx) |
| `AgentAwakeSetting.tsx` | [`src/renderer/src/components/settings/AgentAwakeSetting.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/AgentAwakeSetting.tsx) |
| `AgentCacheTimerSection.tsx` | [`src/renderer/src/components/settings/AgentCacheTimerSection.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/AgentCacheTimerSection.tsx) |
| `AgentSkillSetupPanel.test.tsx` | [`src/renderer/src/components/settings/AgentSkillSetupPanel.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/AgentSkillSetupPanel.test.tsx) |
| `AgentSkillSetupPanel.tsx` | [`src/renderer/src/components/settings/AgentSkillSetupPanel.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/AgentSkillSetupPanel.tsx) |
| `AgentsPane.test.tsx` | [`src/renderer/src/components/settings/AgentsPane.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/AgentsPane.test.tsx) |
| `AgentsPane.tsx` | [`src/renderer/src/components/settings/AgentsPane.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/AgentsPane.tsx) |
| `AppIconSelector.tsx` | [`src/renderer/src/components/settings/AppIconSelector.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/AppIconSelector.tsx) |
| `AppearancePane.test.tsx` | [`src/renderer/src/components/settings/AppearancePane.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/AppearancePane.test.tsx) |
| `AppearancePane.tsx` | [`src/renderer/src/components/settings/AppearancePane.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/AppearancePane.tsx) |
| `AutoRenameBranchFromWorkSetting.tsx` | [`src/renderer/src/components/settings/AutoRenameBranchFromWorkSetting.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/AutoRenameBranchFromWorkSetting.tsx) |
| `AutoRenameBranchPromptEditor.tsx` | [`src/renderer/src/components/settings/AutoRenameBranchPromptEditor.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/AutoRenameBranchPromptEditor.tsx) |
| `BaseRefPicker.tsx` | [`src/renderer/src/components/settings/BaseRefPicker.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/BaseRefPicker.tsx) |
| `BrowserDefaultZoomSetting.tsx` | [`src/renderer/src/components/settings/BrowserDefaultZoomSetting.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/BrowserDefaultZoomSetting.tsx) |
| `BrowserHomePageSetting.tsx` | [`src/renderer/src/components/settings/BrowserHomePageSetting.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/BrowserHomePageSetting.tsx) |
| `BrowserLinkRoutingSetting.tsx` | [`src/renderer/src/components/settings/BrowserLinkRoutingSetting.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/BrowserLinkRoutingSetting.tsx) |
| `BrowserNewProfileDialog.tsx` | [`src/renderer/src/components/settings/BrowserNewProfileDialog.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/BrowserNewProfileDialog.tsx) |
| `BrowserPane.tsx` | [`src/renderer/src/components/settings/BrowserPane.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/BrowserPane.tsx) |
| `BrowserProfileRow.tsx` | [`src/renderer/src/components/settings/BrowserProfileRow.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/BrowserProfileRow.tsx) |
| `BrowserSearchEngineSetting.tsx` | [`src/renderer/src/components/settings/BrowserSearchEngineSetting.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/BrowserSearchEngineSetting.tsx) |
| `BrowserSessionCookiesSection.tsx` | [`src/renderer/src/components/settings/BrowserSessionCookiesSection.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/BrowserSessionCookiesSection.tsx) |
| `BrowserUseCliStep.tsx` | [`src/renderer/src/components/settings/BrowserUseCliStep.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/BrowserUseCliStep.tsx) |
| `BrowserUseComputerUseNotice.tsx` | [`src/renderer/src/components/settings/BrowserUseComputerUseNotice.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/BrowserUseComputerUseNotice.tsx) |
| `BrowserUseCookieImportStep.tsx` | [`src/renderer/src/components/settings/BrowserUseCookieImportStep.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/BrowserUseCookieImportStep.tsx) |
| `BrowserUseEnableSwitch.tsx` | [`src/renderer/src/components/settings/BrowserUseEnableSwitch.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/BrowserUseEnableSwitch.tsx) |
| `BrowserUseExamples.tsx` | [`src/renderer/src/components/settings/BrowserUseExamples.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/BrowserUseExamples.tsx) |
| `BrowserUsePane.tsx` | [`src/renderer/src/components/settings/BrowserUsePane.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/BrowserUsePane.tsx) |
| `BrowserUseSkillStep.test.tsx` | [`src/renderer/src/components/settings/BrowserUseSkillStep.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/BrowserUseSkillStep.test.tsx) |
| `BrowserUseSkillStep.tsx` | [`src/renderer/src/components/settings/BrowserUseSkillStep.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/BrowserUseSkillStep.tsx) |
| `BrowserUseStepBadge.tsx` | [`src/renderer/src/components/settings/BrowserUseStepBadge.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/BrowserUseStepBadge.tsx) |
| `CliAgentSkillSetup.tsx` | [`src/renderer/src/components/settings/CliAgentSkillSetup.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/CliAgentSkillSetup.tsx) |
| `CliRegistrationDialog.tsx` | [`src/renderer/src/components/settings/CliRegistrationDialog.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/CliRegistrationDialog.tsx) |
| `CliSection.test.tsx` | [`src/renderer/src/components/settings/CliSection.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/CliSection.test.tsx) |
| `CliSection.tsx` | [`src/renderer/src/components/settings/CliSection.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/CliSection.tsx) |
| `CliSkillRuntimeSetup.test.tsx` | [`src/renderer/src/components/settings/CliSkillRuntimeSetup.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/CliSkillRuntimeSetup.test.tsx) |
| `CliSkillRuntimeSetup.tsx` | [`src/renderer/src/components/settings/CliSkillRuntimeSetup.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/CliSkillRuntimeSetup.tsx) |
| `CommitMessageAiPane.test.tsx` | [`src/renderer/src/components/settings/CommitMessageAiPane.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/CommitMessageAiPane.test.tsx) |
| `CommitMessageAiPane.tsx` | [`src/renderer/src/components/settings/CommitMessageAiPane.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/CommitMessageAiPane.tsx) |
| `ComputerUsePane.tsx` | [`src/renderer/src/components/settings/ComputerUsePane.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/ComputerUsePane.tsx) |
| `ComputerUseSkillSetupPanel.tsx` | [`src/renderer/src/components/settings/ComputerUseSkillSetupPanel.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/ComputerUseSkillSetupPanel.tsx) |
| `DefaultWindowsProjectRuntimeSetting.test.tsx` | [`src/renderer/src/components/settings/DefaultWindowsProjectRuntimeSetting.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/DefaultWindowsProjectRuntimeSetting.test.tsx) |
| `DefaultWindowsProjectRuntimeSetting.tsx` | [`src/renderer/src/components/settings/DefaultWindowsProjectRuntimeSetting.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/DefaultWindowsProjectRuntimeSetting.tsx) |
| `DeveloperPermissionsPane.tsx` | [`src/renderer/src/components/settings/DeveloperPermissionsPane.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/DeveloperPermissionsPane.tsx) |
| `ExperimentalPane.test.tsx` | [`src/renderer/src/components/settings/ExperimentalPane.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/ExperimentalPane.test.tsx) |
| `ExperimentalPane.tsx` | [`src/renderer/src/components/settings/ExperimentalPane.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/ExperimentalPane.tsx) |
| `FloatingWorkspacePane.test.tsx` | [`src/renderer/src/components/settings/FloatingWorkspacePane.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/FloatingWorkspacePane.test.tsx) |
| `FloatingWorkspacePane.tsx` | [`src/renderer/src/components/settings/FloatingWorkspacePane.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/FloatingWorkspacePane.tsx) |
| `GeneralEditorSettingsSection.tsx` | [`src/renderer/src/components/settings/GeneralEditorSettingsSection.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/GeneralEditorSettingsSection.tsx) |
| `GeneralPane.tsx` | [`src/renderer/src/components/settings/GeneralPane.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/GeneralPane.tsx) |
| `GeneralSupportSection.tsx` | [`src/renderer/src/components/settings/GeneralSupportSection.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/GeneralSupportSection.tsx) |
| `GeneralUpdateSettingsSection.tsx` | [`src/renderer/src/components/settings/GeneralUpdateSettingsSection.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/GeneralUpdateSettingsSection.tsx) |
| `GeneralWorkspaceSettingsSection.tsx` | [`src/renderer/src/components/settings/GeneralWorkspaceSettingsSection.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/GeneralWorkspaceSettingsSection.tsx) |
| `GhosttyImportModal.tsx` | [`src/renderer/src/components/settings/GhosttyImportModal.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/GhosttyImportModal.tsx) |
| `GitPane.tsx` | [`src/renderer/src/components/settings/GitPane.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/GitPane.tsx) |
| `GitProviderApiBudgetPane.tsx` | [`src/renderer/src/components/settings/GitProviderApiBudgetPane.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/GitProviderApiBudgetPane.tsx) |
| `HiddenExperimentalGroup.tsx` | [`src/renderer/src/components/settings/HiddenExperimentalGroup.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/HiddenExperimentalGroup.tsx) |
| `HostedReviewCreationDefaults.tsx` | [`src/renderer/src/components/settings/HostedReviewCreationDefaults.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/HostedReviewCreationDefaults.tsx) |
| `InputPane.tsx` | [`src/renderer/src/components/settings/InputPane.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/InputPane.tsx) |
| `IntegrationsPane.tsx` | [`src/renderer/src/components/settings/IntegrationsPane.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/IntegrationsPane.tsx) |
| `KagiSessionLinkForm.tsx` | [`src/renderer/src/components/settings/KagiSessionLinkForm.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/KagiSessionLinkForm.tsx) |
| `KeybindingsFileActions.tsx` | [`src/renderer/src/components/settings/KeybindingsFileActions.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/KeybindingsFileActions.tsx) |
| `LeftSidebarAppearanceSetting.tsx` | [`src/renderer/src/components/settings/LeftSidebarAppearanceSetting.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/LeftSidebarAppearanceSetting.tsx) |
| `ManageSessionKillDialog.tsx` | [`src/renderer/src/components/settings/ManageSessionKillDialog.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/ManageSessionKillDialog.tsx) |
| `ManageSessionsSection.tsx` | [`src/renderer/src/components/settings/ManageSessionsSection.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/ManageSessionsSection.tsx) |
| `ManageSessionsTable.tsx` | [`src/renderer/src/components/settings/ManageSessionsTable.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/ManageSessionsTable.tsx) |
| `McpConfigFileRow.tsx` | [`src/renderer/src/components/settings/McpConfigFileRow.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/McpConfigFileRow.tsx) |
| `McpConfigSection.tsx` | [`src/renderer/src/components/settings/McpConfigSection.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/McpConfigSection.tsx) |
| `McpMissingConfigList.tsx` | [`src/renderer/src/components/settings/McpMissingConfigList.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/McpMissingConfigList.tsx) |
| `MobileAutoRestoreFitSection.tsx` | [`src/renderer/src/components/settings/MobileAutoRestoreFitSection.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/MobileAutoRestoreFitSection.tsx) |
| `MobileEmulatorAgentControlRow.tsx` | [`src/renderer/src/components/settings/MobileEmulatorAgentControlRow.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/MobileEmulatorAgentControlRow.tsx) |
| `MobileEmulatorExamples.tsx` | [`src/renderer/src/components/settings/MobileEmulatorExamples.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/MobileEmulatorExamples.tsx) |
| `MobileEmulatorSettingsPane.tsx` | [`src/renderer/src/components/settings/MobileEmulatorSettingsPane.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/MobileEmulatorSettingsPane.tsx) |
| `MobileNetworkInterfaceSection.test.tsx` | [`src/renderer/src/components/settings/MobileNetworkInterfaceSection.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/MobileNetworkInterfaceSection.test.tsx) |
| `MobileNetworkInterfaceSection.tsx` | [`src/renderer/src/components/settings/MobileNetworkInterfaceSection.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/MobileNetworkInterfaceSection.tsx) |
| `MobilePairedDevicesSection.tsx` | [`src/renderer/src/components/settings/MobilePairedDevicesSection.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/MobilePairedDevicesSection.tsx) |
| `MobilePairingQrSection.tsx` | [`src/renderer/src/components/settings/MobilePairingQrSection.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/MobilePairingQrSection.tsx) |
| `MobilePane.tsx` | [`src/renderer/src/components/settings/MobilePane.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/MobilePane.tsx) |
| `MobileSettingsPane.tsx` | [`src/renderer/src/components/settings/MobileSettingsPane.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/MobileSettingsPane.tsx) |
| `NotificationSettingToggle.tsx` | [`src/renderer/src/components/settings/NotificationSettingToggle.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/NotificationSettingToggle.tsx) |
| `NotificationSoundSection.tsx` | [`src/renderer/src/components/settings/NotificationSoundSection.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/NotificationSoundSection.tsx) |
| `NotificationsPane.test.tsx` | [`src/renderer/src/components/settings/NotificationsPane.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/NotificationsPane.test.tsx) |
| `NotificationsPane.tsx` | [`src/renderer/src/components/settings/NotificationsPane.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/NotificationsPane.tsx) |
| `OpenAiTranscriptionKeyDialog.tsx` | [`src/renderer/src/components/settings/OpenAiTranscriptionKeyDialog.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/OpenAiTranscriptionKeyDialog.tsx) |
| `OpenAiTranscriptionSettingsRow.tsx` | [`src/renderer/src/components/settings/OpenAiTranscriptionSettingsRow.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/OpenAiTranscriptionSettingsRow.tsx) |
| `OpenInMenuSetting.tsx` | [`src/renderer/src/components/settings/OpenInMenuSetting.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/OpenInMenuSetting.tsx) |
| `OrchestrationExamplesDialog.tsx` | [`src/renderer/src/components/settings/OrchestrationExamplesDialog.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/OrchestrationExamplesDialog.tsx) |
| `OrchestrationPane.test.tsx` | [`src/renderer/src/components/settings/OrchestrationPane.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/OrchestrationPane.test.tsx) |
| `OrchestrationPane.tsx` | [`src/renderer/src/components/settings/OrchestrationPane.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/OrchestrationPane.tsx) |
| `OrchestrationSetupCard.tsx` | [`src/renderer/src/components/settings/OrchestrationSetupCard.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/OrchestrationSetupCard.tsx) |
| `OrchestrationSkillAgentCoverage.test.tsx` | [`src/renderer/src/components/settings/OrchestrationSkillAgentCoverage.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/OrchestrationSkillAgentCoverage.test.tsx) |
| `OrchestrationSkillAgentCoverage.tsx` | [`src/renderer/src/components/settings/OrchestrationSkillAgentCoverage.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/OrchestrationSkillAgentCoverage.tsx) |
| `OrchestrationSkillPromptDialog.tsx` | [`src/renderer/src/components/settings/OrchestrationSkillPromptDialog.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/OrchestrationSkillPromptDialog.tsx) |
| `PrivacyDiagnosticBundleControls.tsx` | [`src/renderer/src/components/settings/PrivacyDiagnosticBundleControls.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/PrivacyDiagnosticBundleControls.tsx) |
| `PrivacyDiagnosticsSection.tsx` | [`src/renderer/src/components/settings/PrivacyDiagnosticsSection.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/PrivacyDiagnosticsSection.tsx) |
| `PrivacyPane.tsx` | [`src/renderer/src/components/settings/PrivacyPane.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/PrivacyPane.tsx) |
| `ProjectWindowsRuntimeSetting.test.tsx` | [`src/renderer/src/components/settings/ProjectWindowsRuntimeSetting.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/ProjectWindowsRuntimeSetting.test.tsx) |
| `ProjectWindowsRuntimeSetting.tsx` | [`src/renderer/src/components/settings/ProjectWindowsRuntimeSetting.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/ProjectWindowsRuntimeSetting.tsx) |
| `ProviderHostScopeControl.tsx` | [`src/renderer/src/components/settings/ProviderHostScopeControl.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/ProviderHostScopeControl.tsx) |
| `QuickCommandsList.tsx` | [`src/renderer/src/components/settings/QuickCommandsList.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/QuickCommandsList.tsx) |
| `QuickCommandsPane.tsx` | [`src/renderer/src/components/settings/QuickCommandsPane.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/QuickCommandsPane.tsx) |
| `QuickCommandsScopeFilter.tsx` | [`src/renderer/src/components/settings/QuickCommandsScopeFilter.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/QuickCommandsScopeFilter.tsx) |
| `RecentTabOrderControl.tsx` | [`src/renderer/src/components/settings/RecentTabOrderControl.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/RecentTabOrderControl.tsx) |
| `RepositoryForkSyncSection.tsx` | [`src/renderer/src/components/settings/RepositoryForkSyncSection.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/RepositoryForkSyncSection.tsx) |
| `RepositoryHooksSection.tsx` | [`src/renderer/src/components/settings/RepositoryHooksSection.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/RepositoryHooksSection.tsx) |
| `RepositoryHostSetupActions.tsx` | [`src/renderer/src/components/settings/RepositoryHostSetupActions.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/RepositoryHostSetupActions.tsx) |
| `RepositoryHostSetupsSection.test.tsx` | [`src/renderer/src/components/settings/RepositoryHostSetupsSection.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/RepositoryHostSetupsSection.test.tsx) |
| `RepositoryHostSetupsSection.tsx` | [`src/renderer/src/components/settings/RepositoryHostSetupsSection.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/RepositoryHostSetupsSection.tsx) |
| `RepositoryIconColorSection.tsx` | [`src/renderer/src/components/settings/RepositoryIconColorSection.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/RepositoryIconColorSection.tsx) |
| `RepositoryIconPicker.tsx` | [`src/renderer/src/components/settings/RepositoryIconPicker.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/RepositoryIconPicker.tsx) |
| `RepositoryIconTabs.tsx` | [`src/renderer/src/components/settings/RepositoryIconTabs.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/RepositoryIconTabs.tsx) |
| `RepositoryPane.tsx` | [`src/renderer/src/components/settings/RepositoryPane.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/RepositoryPane.tsx) |
| `RepositoryPaneDraftInput.test.tsx` | [`src/renderer/src/components/settings/RepositoryPaneDraftInput.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/RepositoryPaneDraftInput.test.tsx) |
| `RepositorySettingsDraftInput.tsx` | [`src/renderer/src/components/settings/RepositorySettingsDraftInput.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/RepositorySettingsDraftInput.tsx) |
| `RepositorySourceControlAiActionRows.tsx` | [`src/renderer/src/components/settings/RepositorySourceControlAiActionRows.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/RepositorySourceControlAiActionRows.tsx) |
| `RepositorySourceControlAiCustomCommand.tsx` | [`src/renderer/src/components/settings/RepositorySourceControlAiCustomCommand.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/RepositorySourceControlAiCustomCommand.tsx) |
| `RepositorySourceControlAiEnablement.tsx` | [`src/renderer/src/components/settings/RepositorySourceControlAiEnablement.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/RepositorySourceControlAiEnablement.tsx) |
| `RepositorySourceControlAiHostedReviewDefaults.tsx` | [`src/renderer/src/components/settings/RepositorySourceControlAiHostedReviewDefaults.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/RepositorySourceControlAiHostedReviewDefaults.tsx) |
| `RepositorySourceControlAiSection.tsx` | [`src/renderer/src/components/settings/RepositorySourceControlAiSection.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/RepositorySourceControlAiSection.tsx) |
| `RepositoryWindowsRuntimeSection.tsx` | [`src/renderer/src/components/settings/RepositoryWindowsRuntimeSection.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/RepositoryWindowsRuntimeSection.tsx) |
| `RepositoryWorktreeDefaultsSection.test.tsx` | [`src/renderer/src/components/settings/RepositoryWorktreeDefaultsSection.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/RepositoryWorktreeDefaultsSection.test.tsx) |
| `RepositoryWorktreeDefaultsSection.tsx` | [`src/renderer/src/components/settings/RepositoryWorktreeDefaultsSection.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/RepositoryWorktreeDefaultsSection.tsx) |
| `RuntimeAccessGrantList.tsx` | [`src/renderer/src/components/settings/RuntimeAccessGrantList.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/RuntimeAccessGrantList.tsx) |
| `RuntimeEnvironmentsPane.tsx` | [`src/renderer/src/components/settings/RuntimeEnvironmentsPane.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/RuntimeEnvironmentsPane.tsx) |
| `RuntimePairingGeneratedUrlRows.tsx` | [`src/renderer/src/components/settings/RuntimePairingGeneratedUrlRows.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/RuntimePairingGeneratedUrlRows.tsx) |
| `RuntimePairingGeneratorForm.tsx` | [`src/renderer/src/components/settings/RuntimePairingGeneratorForm.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/RuntimePairingGeneratorForm.tsx) |
| `RuntimePairingUrlGenerator.tsx` | [`src/renderer/src/components/settings/RuntimePairingUrlGenerator.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/RuntimePairingUrlGenerator.tsx) |
| `SearchableSetting.tsx` | [`src/renderer/src/components/settings/SearchableSetting.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/SearchableSetting.tsx) |
| `Settings.tsx` | [`src/renderer/src/components/settings/Settings.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/Settings.tsx) |
| `SettingsFormControls.font-autocomplete.test.tsx` | [`src/renderer/src/components/settings/SettingsFormControls.font-autocomplete.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/SettingsFormControls.font-autocomplete.test.tsx) |
| `SettingsFormControls.tsx` | [`src/renderer/src/components/settings/SettingsFormControls.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/SettingsFormControls.tsx) |
| `SettingsSection.tsx` | [`src/renderer/src/components/settings/SettingsSection.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/SettingsSection.tsx) |
| `SettingsSetupGuidePane.tsx` | [`src/renderer/src/components/settings/SettingsSetupGuidePane.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/SettingsSetupGuidePane.tsx) |
| `SettingsSidebar.test.tsx` | [`src/renderer/src/components/settings/SettingsSidebar.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/SettingsSidebar.test.tsx) |
| `SettingsSidebar.tsx` | [`src/renderer/src/components/settings/SettingsSidebar.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/SettingsSidebar.tsx) |
| `ShortcutBindingSubRow.tsx` | [`src/renderer/src/components/settings/ShortcutBindingSubRow.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/ShortcutBindingSubRow.tsx) |
| `ShortcutCommandBlock.tsx` | [`src/renderer/src/components/settings/ShortcutCommandBlock.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/ShortcutCommandBlock.tsx) |
| `ShortcutFilterRail.tsx` | [`src/renderer/src/components/settings/ShortcutFilterRail.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/ShortcutFilterRail.tsx) |
| `ShortcutRecorderButton.tsx` | [`src/renderer/src/components/settings/ShortcutRecorderButton.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/ShortcutRecorderButton.tsx) |
| `ShortcutRemoveButton.tsx` | [`src/renderer/src/components/settings/ShortcutRemoveButton.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/ShortcutRemoveButton.tsx) |
| `ShortcutRowsList.tsx` | [`src/renderer/src/components/settings/ShortcutRowsList.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/ShortcutRowsList.tsx) |
| `ShortcutTerminalPolicyControl.tsx` | [`src/renderer/src/components/settings/ShortcutTerminalPolicyControl.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/ShortcutTerminalPolicyControl.tsx) |
| `ShortcutsPane.tsx` | [`src/renderer/src/components/settings/ShortcutsPane.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/ShortcutsPane.tsx) |
| `SourceControlActionRecipeRow.tsx` | [`src/renderer/src/components/settings/SourceControlActionRecipeRow.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/SourceControlActionRecipeRow.tsx) |
| `SourceControlAiActionRecipeDefaults.tsx` | [`src/renderer/src/components/settings/SourceControlAiActionRecipeDefaults.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/SourceControlAiActionRecipeDefaults.tsx) |
| `SparsePresetSettingsSection.test.tsx` | [`src/renderer/src/components/settings/SparsePresetSettingsSection.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/SparsePresetSettingsSection.test.tsx) |
| `SparsePresetSettingsSection.tsx` | [`src/renderer/src/components/settings/SparsePresetSettingsSection.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/SparsePresetSettingsSection.tsx) |
| `SshDestructiveActionDialog.tsx` | [`src/renderer/src/components/settings/SshDestructiveActionDialog.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/SshDestructiveActionDialog.tsx) |
| `SshPane.tsx` | [`src/renderer/src/components/settings/SshPane.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/SshPane.tsx) |
| `SshPassphraseDialog.tsx` | [`src/renderer/src/components/settings/SshPassphraseDialog.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/SshPassphraseDialog.tsx) |
| `SshTargetCard.tsx` | [`src/renderer/src/components/settings/SshTargetCard.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/SshTargetCard.tsx) |
| `SshTargetDestructiveActions.tsx` | [`src/renderer/src/components/settings/SshTargetDestructiveActions.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/SshTargetDestructiveActions.tsx) |
| `SshTargetForm.tsx` | [`src/renderer/src/components/settings/SshTargetForm.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/SshTargetForm.tsx) |
| `TasksPane.tsx` | [`src/renderer/src/components/settings/TasksPane.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/TasksPane.tsx) |
| `TerminalAdvancedSection.tsx` | [`src/renderer/src/components/settings/TerminalAdvancedSection.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/TerminalAdvancedSection.tsx) |
| `TerminalAppearanceSection.tsx` | [`src/renderer/src/components/settings/TerminalAppearanceSection.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/TerminalAppearanceSection.tsx) |
| `TerminalCursorAppearanceSection.tsx` | [`src/renderer/src/components/settings/TerminalCursorAppearanceSection.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/TerminalCursorAppearanceSection.tsx) |
| `TerminalFontSizeSetting.tsx` | [`src/renderer/src/components/settings/TerminalFontSizeSetting.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/TerminalFontSizeSetting.tsx) |
| `TerminalInteractionSection.tsx` | [`src/renderer/src/components/settings/TerminalInteractionSection.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/TerminalInteractionSection.tsx) |
| `TerminalMacKeyboardSection.tsx` | [`src/renderer/src/components/settings/TerminalMacKeyboardSection.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/TerminalMacKeyboardSection.tsx) |
| `TerminalPane.tsx` | [`src/renderer/src/components/settings/TerminalPane.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/TerminalPane.tsx) |
| `TerminalPaneAppearanceSection.tsx` | [`src/renderer/src/components/settings/TerminalPaneAppearanceSection.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/TerminalPaneAppearanceSection.tsx) |
| `TerminalRenderingSection.tsx` | [`src/renderer/src/components/settings/TerminalRenderingSection.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/TerminalRenderingSection.tsx) |
| `TerminalSettingsPreview.lifecycle.test.tsx` | [`src/renderer/src/components/settings/TerminalSettingsPreview.lifecycle.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/TerminalSettingsPreview.lifecycle.test.tsx) |
| `TerminalSettingsPreview.tsx` | [`src/renderer/src/components/settings/TerminalSettingsPreview.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/TerminalSettingsPreview.tsx) |
| `TerminalSetupScriptSection.tsx` | [`src/renderer/src/components/settings/TerminalSetupScriptSection.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/TerminalSetupScriptSection.tsx) |
| `TerminalThemeSections.tsx` | [`src/renderer/src/components/settings/TerminalThemeSections.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/TerminalThemeSections.tsx) |
| `TerminalTypographyAppearanceSection.tsx` | [`src/renderer/src/components/settings/TerminalTypographyAppearanceSection.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/TerminalTypographyAppearanceSection.tsx) |
| `TerminalWindowSection.tsx` | [`src/renderer/src/components/settings/TerminalWindowSection.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/TerminalWindowSection.tsx) |
| `TerminalWindowsShellSection.tsx` | [`src/renderer/src/components/settings/TerminalWindowsShellSection.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/TerminalWindowsShellSection.tsx) |
| `UIZoomControl.tsx` | [`src/renderer/src/components/settings/UIZoomControl.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/UIZoomControl.tsx) |
| `VoiceDictationSettingsSection.tsx` | [`src/renderer/src/components/settings/VoiceDictationSettingsSection.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/VoiceDictationSettingsSection.tsx) |
| `VoicePane.test.tsx` | [`src/renderer/src/components/settings/VoicePane.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/VoicePane.test.tsx) |
| `VoicePane.tsx` | [`src/renderer/src/components/settings/VoicePane.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/VoicePane.tsx) |
| `VoiceSpeechModelSection.test.tsx` | [`src/renderer/src/components/settings/VoiceSpeechModelSection.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/VoiceSpeechModelSection.test.tsx) |
| `VoiceSpeechModelSection.tsx` | [`src/renderer/src/components/settings/VoiceSpeechModelSection.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/VoiceSpeechModelSection.tsx) |
| `WarpThemeImportButton.tsx` | [`src/renderer/src/components/settings/WarpThemeImportButton.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/WarpThemeImportButton.tsx) |
| `WarpThemeImportModal.tsx` | [`src/renderer/src/components/settings/WarpThemeImportModal.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/WarpThemeImportModal.tsx) |
| `WorkspaceDirectorySetting.test.tsx` | [`src/renderer/src/components/settings/WorkspaceDirectorySetting.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/WorkspaceDirectorySetting.test.tsx) |
| `WorkspaceDirectorySetting.tsx` | [`src/renderer/src/components/settings/WorkspaceDirectorySetting.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/WorkspaceDirectorySetting.tsx) |
| `WorktreeSymlinksSection.tsx` | [`src/renderer/src/components/settings/WorktreeSymlinksSection.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/WorktreeSymlinksSection.tsx) |
| `WslCliRegistration.tsx` | [`src/renderer/src/components/settings/WslCliRegistration.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/WslCliRegistration.tsx) |
| `YamlThemeImportButton.tsx` | [`src/renderer/src/components/settings/YamlThemeImportButton.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/YamlThemeImportButton.tsx) |
| `cli-source-control-integration-cards.test.tsx` | [`src/renderer/src/components/settings/cli-source-control-integration-cards.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/cli-source-control-integration-cards.test.tsx) |
| `cli-source-control-integration-cards.tsx` | [`src/renderer/src/components/settings/cli-source-control-integration-cards.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/cli-source-control-integration-cards.tsx) |
| `computer-use-permission-definitions.tsx` | [`src/renderer/src/components/settings/computer-use-permission-definitions.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/computer-use-permission-definitions.tsx) |
| `integration-card-presentation.tsx` | [`src/renderer/src/components/settings/integration-card-presentation.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/integration-card-presentation.tsx) |
| `integration-card-shell.tsx` | [`src/renderer/src/components/settings/integration-card-shell.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/integration-card-shell.tsx) |
| `jira-integration-card.test.tsx` | [`src/renderer/src/components/settings/jira-integration-card.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/jira-integration-card.test.tsx) |
| `jira-integration-card.tsx` | [`src/renderer/src/components/settings/jira-integration-card.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/jira-integration-card.tsx) |
| `orca-logo-settings-icon.tsx` | [`src/renderer/src/components/settings/orca-logo-settings-icon.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/orca-logo-settings-icon.tsx) |
| `provider-rate-limit-scope-panels.test.tsx` | [`src/renderer/src/components/settings/provider-rate-limit-scope-panels.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/provider-rate-limit-scope-panels.test.tsx) |
| `repository-host-add-project-steps.tsx` | [`src/renderer/src/components/settings/repository-host-add-project-steps.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/repository-host-add-project-steps.tsx) |
| `settings-setup-guide-progress-hook.test.tsx` | [`src/renderer/src/components/settings/settings-setup-guide-progress-hook.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/settings-setup-guide-progress-hook.test.tsx) |
| `source-control-integration-cards.tsx` | [`src/renderer/src/components/settings/source-control-integration-cards.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/source-control-integration-cards.tsx) |
| `sparse-preset-directory-preview.tsx` | [`src/renderer/src/components/settings/sparse-preset-directory-preview.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/sparse-preset-directory-preview.tsx) |
| `sparse-preset-draft-editor.tsx` | [`src/renderer/src/components/settings/sparse-preset-draft-editor.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/sparse-preset-draft-editor.tsx) |
| `sparse-preset-settings-row.tsx` | [`src/renderer/src/components/settings/sparse-preset-settings-row.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/sparse-preset-settings-row.tsx) |
| `task-tracker-integration-cards.test.tsx` | [`src/renderer/src/components/settings/task-tracker-integration-cards.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/task-tracker-integration-cards.test.tsx) |
| `task-tracker-integration-cards.tsx` | [`src/renderer/src/components/settings/task-tracker-integration-cards.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/task-tracker-integration-cards.tsx) |
| `terminal-window-color-groups.tsx` | [`src/renderer/src/components/settings/terminal-window-color-groups.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/terminal-window-color-groups.tsx) |
| `token-source-control-integration-cards.tsx` | [`src/renderer/src/components/settings/token-source-control-integration-cards.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/settings/token-source-control-integration-cards.tsx) |

## Desktop App - File Editor (Monaco & Markdown)

*Total: 69 arquivos*

| Arquivo | Caminho Completo |
| :--- | :--- |
| `ChangesModeView.test.tsx` | [`src/renderer/src/components/editor/ChangesModeView.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/editor/ChangesModeView.test.tsx) |
| `ChangesModeView.tsx` | [`src/renderer/src/components/editor/ChangesModeView.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/editor/ChangesModeView.tsx) |
| `CheckRunDetailsPanel.tsx` | [`src/renderer/src/components/editor/CheckRunDetailsPanel.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/editor/CheckRunDetailsPanel.tsx) |
| `CodeBlockCopyButton.tsx` | [`src/renderer/src/components/editor/CodeBlockCopyButton.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/editor/CodeBlockCopyButton.tsx) |
| `CombinedDiffFileTree.tsx` | [`src/renderer/src/components/editor/CombinedDiffFileTree.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/editor/CombinedDiffFileTree.tsx) |
| `CombinedDiffViewer.tsx` | [`src/renderer/src/components/editor/CombinedDiffViewer.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/editor/CombinedDiffViewer.tsx) |
| `ConflictComponents.test.tsx` | [`src/renderer/src/components/editor/ConflictComponents.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/editor/ConflictComponents.test.tsx) |
| `ConflictComponents.tsx` | [`src/renderer/src/components/editor/ConflictComponents.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/editor/ConflictComponents.tsx) |
| `ConflictReviewFileTree.tsx` | [`src/renderer/src/components/editor/ConflictReviewFileTree.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/editor/ConflictReviewFileTree.tsx) |
| `CsvViewer.tsx` | [`src/renderer/src/components/editor/CsvViewer.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/editor/CsvViewer.tsx) |
| `DiffNotesSendMenu.tsx` | [`src/renderer/src/components/editor/DiffNotesSendMenu.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/editor/DiffNotesSendMenu.tsx) |
| `DiffSectionBody.tsx` | [`src/renderer/src/components/editor/DiffSectionBody.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/editor/DiffSectionBody.tsx) |
| `DiffSectionHeader.tsx` | [`src/renderer/src/components/editor/DiffSectionHeader.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/editor/DiffSectionHeader.tsx) |
| `DiffSectionItem.tsx` | [`src/renderer/src/components/editor/DiffSectionItem.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/editor/DiffSectionItem.tsx) |
| `DiffViewer.tsx` | [`src/renderer/src/components/editor/DiffViewer.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/editor/DiffViewer.tsx) |
| `EditorAutosaveController.tsx` | [`src/renderer/src/components/editor/EditorAutosaveController.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/editor/EditorAutosaveController.tsx) |
| `EditorContent.test.tsx` | [`src/renderer/src/components/editor/EditorContent.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/editor/EditorContent.test.tsx) |
| `EditorContent.tsx` | [`src/renderer/src/components/editor/EditorContent.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/editor/EditorContent.tsx) |
| `EditorPanel.tsx` | [`src/renderer/src/components/editor/EditorPanel.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/editor/EditorPanel.tsx) |
| `EditorPanelHeader.tsx` | [`src/renderer/src/components/editor/EditorPanelHeader.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/editor/EditorPanelHeader.tsx) |
| `EditorPanelHeaderPath.tsx` | [`src/renderer/src/components/editor/EditorPanelHeaderPath.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/editor/EditorPanelHeaderPath.tsx) |
| `EditorPanelMarkdownActionsMenu.tsx` | [`src/renderer/src/components/editor/EditorPanelMarkdownActionsMenu.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/editor/EditorPanelMarkdownActionsMenu.tsx) |
| `EditorPanelShell.tsx` | [`src/renderer/src/components/editor/EditorPanelShell.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/editor/EditorPanelShell.tsx) |
| `EditorViewToggle.tsx` | [`src/renderer/src/components/editor/EditorViewToggle.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/editor/EditorViewToggle.tsx) |
| `ImageDiffViewer.tsx` | [`src/renderer/src/components/editor/ImageDiffViewer.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/editor/ImageDiffViewer.tsx) |
| `ImageViewer.test.tsx` | [`src/renderer/src/components/editor/ImageViewer.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/editor/ImageViewer.test.tsx) |
| `ImageViewer.tsx` | [`src/renderer/src/components/editor/ImageViewer.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/editor/ImageViewer.tsx) |
| `ImageViewerPopup.tsx` | [`src/renderer/src/components/editor/ImageViewerPopup.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/editor/ImageViewerPopup.tsx) |
| `IpynbViewer.tsx` | [`src/renderer/src/components/editor/IpynbViewer.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/editor/IpynbViewer.tsx) |
| `LargeDiffFallback.tsx` | [`src/renderer/src/components/editor/LargeDiffFallback.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/editor/LargeDiffFallback.tsx) |
| `MarkdownPreview.link-routing.interaction.test.tsx` | [`src/renderer/src/components/editor/MarkdownPreview.link-routing.interaction.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/editor/MarkdownPreview.link-routing.interaction.test.tsx) |
| `MarkdownPreview.tsx` | [`src/renderer/src/components/editor/MarkdownPreview.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/editor/MarkdownPreview.tsx) |
| `MarkdownTableOfContentsPanel.test.tsx` | [`src/renderer/src/components/editor/MarkdownTableOfContentsPanel.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/editor/MarkdownTableOfContentsPanel.test.tsx) |
| `MarkdownTableOfContentsPanel.tsx` | [`src/renderer/src/components/editor/MarkdownTableOfContentsPanel.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/editor/MarkdownTableOfContentsPanel.tsx) |
| `MarkdownTemplatePicker.tsx` | [`src/renderer/src/components/editor/MarkdownTemplatePicker.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/editor/MarkdownTemplatePicker.tsx) |
| `MermaidBlock.tsx` | [`src/renderer/src/components/editor/MermaidBlock.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/editor/MermaidBlock.tsx) |
| `MermaidViewer.tsx` | [`src/renderer/src/components/editor/MermaidViewer.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/editor/MermaidViewer.tsx) |
| `MonacoCodeExcerpt.tsx` | [`src/renderer/src/components/editor/MonacoCodeExcerpt.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/editor/MonacoCodeExcerpt.tsx) |
| `MonacoEditor.tsx` | [`src/renderer/src/components/editor/MonacoEditor.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/editor/MonacoEditor.tsx) |
| `MonacoGutterContextMenu.tsx` | [`src/renderer/src/components/editor/MonacoGutterContextMenu.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/editor/MonacoGutterContextMenu.tsx) |
| `NotesSendMenu.test.tsx` | [`src/renderer/src/components/editor/NotesSendMenu.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/editor/NotesSendMenu.test.tsx) |
| `NotesSendMenu.tsx` | [`src/renderer/src/components/editor/NotesSendMenu.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/editor/NotesSendMenu.tsx) |
| `PdfFind.tsx` | [`src/renderer/src/components/editor/PdfFind.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/editor/PdfFind.tsx) |
| `PdfViewer.tsx` | [`src/renderer/src/components/editor/PdfViewer.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/editor/PdfViewer.tsx) |
| `ReviewNotesSendMenuContent.test.tsx` | [`src/renderer/src/components/editor/ReviewNotesSendMenuContent.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/editor/ReviewNotesSendMenuContent.test.tsx) |
| `ReviewNotesSendMenuContent.tsx` | [`src/renderer/src/components/editor/ReviewNotesSendMenuContent.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/editor/ReviewNotesSendMenuContent.tsx) |
| `RichMarkdownAnnotationOverlay.tsx` | [`src/renderer/src/components/editor/RichMarkdownAnnotationOverlay.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/editor/RichMarkdownAnnotationOverlay.tsx) |
| `RichMarkdownCodeBlock.tsx` | [`src/renderer/src/components/editor/RichMarkdownCodeBlock.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/editor/RichMarkdownCodeBlock.tsx) |
| `RichMarkdownDocLinkMenu.tsx` | [`src/renderer/src/components/editor/RichMarkdownDocLinkMenu.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/editor/RichMarkdownDocLinkMenu.tsx) |
| `RichMarkdownEditor.tsx` | [`src/renderer/src/components/editor/RichMarkdownEditor.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/editor/RichMarkdownEditor.tsx) |
| `RichMarkdownEditorSurface.tsx` | [`src/renderer/src/components/editor/RichMarkdownEditorSurface.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/editor/RichMarkdownEditorSurface.tsx) |
| `RichMarkdownEmojiMenu.tsx` | [`src/renderer/src/components/editor/RichMarkdownEmojiMenu.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/editor/RichMarkdownEmojiMenu.tsx) |
| `RichMarkdownErrorBoundary.tsx` | [`src/renderer/src/components/editor/RichMarkdownErrorBoundary.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/editor/RichMarkdownErrorBoundary.tsx) |
| `RichMarkdownLinkBubble.tsx` | [`src/renderer/src/components/editor/RichMarkdownLinkBubble.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/editor/RichMarkdownLinkBubble.tsx) |
| `RichMarkdownReviewNoteLayer.tsx` | [`src/renderer/src/components/editor/RichMarkdownReviewNoteLayer.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/editor/RichMarkdownReviewNoteLayer.tsx) |
| `RichMarkdownReviewRailActions.tsx` | [`src/renderer/src/components/editor/RichMarkdownReviewRailActions.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/editor/RichMarkdownReviewRailActions.tsx) |
| `RichMarkdownSearchBar.tsx` | [`src/renderer/src/components/editor/RichMarkdownSearchBar.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/editor/RichMarkdownSearchBar.tsx) |
| `RichMarkdownSlashMenu.test.tsx` | [`src/renderer/src/components/editor/RichMarkdownSlashMenu.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/editor/RichMarkdownSlashMenu.test.tsx) |
| `RichMarkdownSlashMenu.tsx` | [`src/renderer/src/components/editor/RichMarkdownSlashMenu.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/editor/RichMarkdownSlashMenu.tsx) |
| `RichMarkdownToolbar.tsx` | [`src/renderer/src/components/editor/RichMarkdownToolbar.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/editor/RichMarkdownToolbar.tsx) |
| `RichMarkdownToolbarButton.tsx` | [`src/renderer/src/components/editor/RichMarkdownToolbarButton.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/editor/RichMarkdownToolbarButton.tsx) |
| `UntitledFileRenameDialog.tsx` | [`src/renderer/src/components/editor/UntitledFileRenameDialog.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/editor/UntitledFileRenameDialog.tsx) |
| `combined-diff-file-tree-row.tsx` | [`src/renderer/src/components/editor/combined-diff-file-tree-row.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/editor/combined-diff-file-tree-row.tsx) |
| `rich-markdown-commands.tsx` | [`src/renderer/src/components/editor/rich-markdown-commands.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/editor/rich-markdown-commands.tsx) |
| `rich-markdown-heading-slash-commands.tsx` | [`src/renderer/src/components/editor/rich-markdown-heading-slash-commands.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/editor/rich-markdown-heading-slash-commands.tsx) |
| `rich-markdown-slash-command-catalog.tsx` | [`src/renderer/src/components/editor/rich-markdown-slash-command-catalog.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/editor/rich-markdown-slash-command-catalog.tsx) |
| `rich-markdown-slash-commands.tsx` | [`src/renderer/src/components/editor/rich-markdown-slash-commands.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/editor/rich-markdown-slash-commands.tsx) |
| `useContextualCopySetup.tsx` | [`src/renderer/src/components/editor/useContextualCopySetup.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/editor/useContextualCopySetup.tsx) |
| `useEditorPanelContentState.test.tsx` | [`src/renderer/src/components/editor/useEditorPanelContentState.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/editor/useEditorPanelContentState.test.tsx) |

## Desktop App - Browser & Mobile Emulator Preview

*Total: 41 arquivos*

| Arquivo | Caminho Completo |
| :--- | :--- |
| `BrowserAddressBar.test.tsx` | [`src/renderer/src/components/browser-pane/BrowserAddressBar.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/browser-pane/BrowserAddressBar.test.tsx) |
| `BrowserAddressBar.tsx` | [`src/renderer/src/components/browser-pane/BrowserAddressBar.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/browser-pane/BrowserAddressBar.tsx) |
| `BrowserFind.tsx` | [`src/renderer/src/components/browser-pane/BrowserFind.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/browser-pane/BrowserFind.tsx) |
| `BrowserImportHintButton.tsx` | [`src/renderer/src/components/browser-pane/BrowserImportHintButton.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/browser-pane/BrowserImportHintButton.tsx) |
| `BrowserMobileDriverOverlay.tsx` | [`src/renderer/src/components/browser-pane/BrowserMobileDriverOverlay.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/browser-pane/BrowserMobileDriverOverlay.tsx) |
| `BrowserPane.tsx` | [`src/renderer/src/components/browser-pane/BrowserPane.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/browser-pane/BrowserPane.tsx) |
| `BrowserPaneOverlayLayer.test.tsx` | [`src/renderer/src/components/browser-pane/BrowserPaneOverlayLayer.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/browser-pane/BrowserPaneOverlayLayer.test.tsx) |
| `BrowserPaneOverlayLayer.tsx` | [`src/renderer/src/components/browser-pane/BrowserPaneOverlayLayer.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/browser-pane/BrowserPaneOverlayLayer.tsx) |
| `BrowserToolbarMenu.tsx` | [`src/renderer/src/components/browser-pane/BrowserToolbarMenu.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/browser-pane/BrowserToolbarMenu.tsx) |
| `GrabConfirmationSheet.tsx` | [`src/renderer/src/components/browser-pane/GrabConfirmationSheet.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/browser-pane/GrabConfirmationSheet.tsx) |
| `browser-toolbar-menu-dropdown.tsx` | [`src/renderer/src/components/browser-pane/browser-toolbar-menu-dropdown.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/browser-pane/browser-toolbar-menu-dropdown.tsx) |
| `browser-toolbar-profile-dialogs.tsx` | [`src/renderer/src/components/browser-pane/browser-toolbar-profile-dialogs.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/browser-pane/browser-toolbar-profile-dialogs.tsx) |
| `EmulatorPane.tsx` | [`src/renderer/src/components/emulator-pane/EmulatorPane.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/emulator-pane/EmulatorPane.tsx) |
| `EmulatorPaneOverlayLayer.tsx` | [`src/renderer/src/components/emulator-pane/EmulatorPaneOverlayLayer.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/emulator-pane/EmulatorPaneOverlayLayer.tsx) |
| `MobileEmulatorAgentSetupGuide.tsx` | [`src/renderer/src/components/emulator-pane/MobileEmulatorAgentSetupGuide.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/emulator-pane/MobileEmulatorAgentSetupGuide.tsx) |
| `MobileEmulatorAgentSetupGuideLayer.tsx` | [`src/renderer/src/components/emulator-pane/MobileEmulatorAgentSetupGuideLayer.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/emulator-pane/MobileEmulatorAgentSetupGuideLayer.tsx) |
| `MobileEmulatorAgentSetupGuideSteps.tsx` | [`src/renderer/src/components/emulator-pane/MobileEmulatorAgentSetupGuideSteps.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/emulator-pane/MobileEmulatorAgentSetupGuideSteps.tsx) |
| `MobileEmulatorTabIntroCallout.test.tsx` | [`src/renderer/src/components/emulator-pane/MobileEmulatorTabIntroCallout.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/emulator-pane/MobileEmulatorTabIntroCallout.test.tsx) |
| `MobileEmulatorTabIntroCallout.tsx` | [`src/renderer/src/components/emulator-pane/MobileEmulatorTabIntroCallout.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/emulator-pane/MobileEmulatorTabIntroCallout.tsx) |
| `emulator-device-frame.input.test.tsx` | [`src/renderer/src/components/emulator-pane/emulator-device-frame.input.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/emulator-pane/emulator-device-frame.input.test.tsx) |
| `emulator-device-frame.tsx` | [`src/renderer/src/components/emulator-pane/emulator-device-frame.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/emulator-pane/emulator-device-frame.tsx) |
| `emulator-pane-toolbar.tsx` | [`src/renderer/src/components/emulator-pane/emulator-pane-toolbar.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/emulator-pane/emulator-pane-toolbar.tsx) |
| `emulator-phone-hardware-buttons.tsx` | [`src/renderer/src/components/emulator-pane/emulator-phone-hardware-buttons.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/emulator-pane/emulator-phone-hardware-buttons.tsx) |
| `emulator-screen-stream-content.test.tsx` | [`src/renderer/src/components/emulator-pane/emulator-screen-stream-content.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/emulator-pane/emulator-screen-stream-content.test.tsx) |
| `emulator-screen-stream-content.tsx` | [`src/renderer/src/components/emulator-pane/emulator-screen-stream-content.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/emulator-pane/emulator-screen-stream-content.tsx) |
| `emulator-unavailable-pane.tsx` | [`src/renderer/src/components/emulator-pane/emulator-unavailable-pane.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/emulator-pane/emulator-unavailable-pane.tsx) |
| `mobile-emulator-hidden-toast.test.tsx` | [`src/renderer/src/components/emulator-pane/mobile-emulator-hidden-toast.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/emulator-pane/mobile-emulator-hidden-toast.test.tsx) |
| `mobile-emulator-hidden-toast.tsx` | [`src/renderer/src/components/emulator-pane/mobile-emulator-hidden-toast.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/emulator-pane/mobile-emulator-hidden-toast.tsx) |
| `use-emulator-pane-session.test.tsx` | [`src/renderer/src/components/emulator-pane/use-emulator-pane-session.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/emulator-pane/use-emulator-pane-session.test.tsx) |
| `use-mobile-emulator-tab-intro-actions.test.tsx` | [`src/renderer/src/components/emulator-pane/use-mobile-emulator-tab-intro-actions.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/emulator-pane/use-mobile-emulator-tab-intro-actions.test.tsx) |
| `MobileBrandIcons.tsx` | [`src/renderer/src/components/mobile/MobileBrandIcons.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/mobile/MobileBrandIcons.tsx) |
| `MobileHero.tsx` | [`src/renderer/src/components/mobile/MobileHero.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/mobile/MobileHero.tsx) |
| `MobileHeroIntro.tsx` | [`src/renderer/src/components/mobile/MobileHeroIntro.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/mobile/MobileHeroIntro.tsx) |
| `MobileHeroPairedDevices.tsx` | [`src/renderer/src/components/mobile/MobileHeroPairedDevices.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/mobile/MobileHeroPairedDevices.tsx) |
| `MobilePage.tsx` | [`src/renderer/src/components/mobile/MobilePage.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/mobile/MobilePage.tsx) |
| `MobilePageContent.tsx` | [`src/renderer/src/components/mobile/MobilePageContent.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/mobile/MobilePageContent.tsx) |
| `MobilePageToolbar.tsx` | [`src/renderer/src/components/mobile/MobilePageToolbar.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/mobile/MobilePageToolbar.tsx) |
| `PhoneCarousel.tsx` | [`src/renderer/src/components/mobile/PhoneCarousel.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/mobile/PhoneCarousel.tsx) |
| `HomeSlide.tsx` | [`src/renderer/src/components/mobile/slides/HomeSlide.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/mobile/slides/HomeSlide.tsx) |
| `TerminalSlide.tsx` | [`src/renderer/src/components/mobile/slides/TerminalSlide.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/mobile/slides/TerminalSlide.tsx) |
| `WorktreeListSlide.tsx` | [`src/renderer/src/components/mobile/slides/WorktreeListSlide.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/mobile/slides/WorktreeListSlide.tsx) |

## Desktop App - Onboarding & Interactive Guides

*Total: 44 arquivos*

| Arquivo | Caminho Completo |
| :--- | :--- |
| `ContextualTourArrow.tsx` | [`src/renderer/src/components/contextual-tours/ContextualTourArrow.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/contextual-tours/ContextualTourArrow.tsx) |
| `ContextualTourControl.tsx` | [`src/renderer/src/components/contextual-tours/ContextualTourControl.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/contextual-tours/ContextualTourControl.tsx) |
| `ContextualTourOverlay.test.tsx` | [`src/renderer/src/components/contextual-tours/ContextualTourOverlay.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/contextual-tours/ContextualTourOverlay.test.tsx) |
| `ContextualTourOverlay.tsx` | [`src/renderer/src/components/contextual-tours/ContextualTourOverlay.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/contextual-tours/ContextualTourOverlay.tsx) |
| `ContextualTourOverlaySurface.tsx` | [`src/renderer/src/components/contextual-tours/ContextualTourOverlaySurface.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/contextual-tours/ContextualTourOverlaySurface.tsx) |
| `ContextualTourProgressDots.tsx` | [`src/renderer/src/components/contextual-tours/ContextualTourProgressDots.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/contextual-tours/ContextualTourProgressDots.tsx) |
| `CliFeatureTipVisual.tsx` | [`src/renderer/src/components/feature-tips/CliFeatureTipVisual.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/feature-tips/CliFeatureTipVisual.tsx) |
| `CliSkillSetupTerminal.tsx` | [`src/renderer/src/components/feature-tips/CliSkillSetupTerminal.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/feature-tips/CliSkillSetupTerminal.tsx) |
| `CmdJPaletteFeatureTipVisual.test.tsx` | [`src/renderer/src/components/feature-tips/CmdJPaletteFeatureTipVisual.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/feature-tips/CmdJPaletteFeatureTipVisual.test.tsx) |
| `CmdJPaletteFeatureTipVisual.tsx` | [`src/renderer/src/components/feature-tips/CmdJPaletteFeatureTipVisual.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/feature-tips/CmdJPaletteFeatureTipVisual.tsx) |
| `CmdJPaletteTipDialog.test.tsx` | [`src/renderer/src/components/feature-tips/CmdJPaletteTipDialog.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/feature-tips/CmdJPaletteTipDialog.test.tsx) |
| `CmdJPaletteTipDialog.tsx` | [`src/renderer/src/components/feature-tips/CmdJPaletteTipDialog.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/feature-tips/CmdJPaletteTipDialog.tsx) |
| `FeatureTipActions.tsx` | [`src/renderer/src/components/feature-tips/FeatureTipActions.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/feature-tips/FeatureTipActions.tsx) |
| `FeatureTipsModal.tsx` | [`src/renderer/src/components/feature-tips/FeatureTipsModal.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/feature-tips/FeatureTipsModal.tsx) |
| `AgentFeatureSetupStep.test.tsx` | [`src/renderer/src/components/onboarding/AgentFeatureSetupStep.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/onboarding/AgentFeatureSetupStep.test.tsx) |
| `AgentFeatureSetupStep.tsx` | [`src/renderer/src/components/onboarding/AgentFeatureSetupStep.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/onboarding/AgentFeatureSetupStep.tsx) |
| `AgentStep.test.tsx` | [`src/renderer/src/components/onboarding/AgentStep.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/onboarding/AgentStep.test.tsx) |
| `AgentStep.tsx` | [`src/renderer/src/components/onboarding/AgentStep.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/onboarding/AgentStep.tsx) |
| `FeatureSetupChecklist.tsx` | [`src/renderer/src/components/onboarding/FeatureSetupChecklist.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/onboarding/FeatureSetupChecklist.tsx) |
| `FeatureSetupInlineTerminal.tsx` | [`src/renderer/src/components/onboarding/FeatureSetupInlineTerminal.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/onboarding/FeatureSetupInlineTerminal.tsx) |
| `GhosttyDiscoveryRow.tsx` | [`src/renderer/src/components/onboarding/GhosttyDiscoveryRow.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/onboarding/GhosttyDiscoveryRow.tsx) |
| `IntegrationsStep.tsx` | [`src/renderer/src/components/onboarding/IntegrationsStep.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/onboarding/IntegrationsStep.tsx) |
| `NotificationStep.test.tsx` | [`src/renderer/src/components/onboarding/NotificationStep.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/onboarding/NotificationStep.test.tsx) |
| `NotificationStep.tsx` | [`src/renderer/src/components/onboarding/NotificationStep.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/onboarding/NotificationStep.tsx) |
| `OnboardingFlow.test.tsx` | [`src/renderer/src/components/onboarding/OnboardingFlow.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/onboarding/OnboardingFlow.test.tsx) |
| `OnboardingFlow.tsx` | [`src/renderer/src/components/onboarding/OnboardingFlow.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/onboarding/OnboardingFlow.tsx) |
| `OnboardingFooter.tsx` | [`src/renderer/src/components/onboarding/OnboardingFooter.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/onboarding/OnboardingFooter.tsx) |
| `OnboardingInlineCommandTerminal.tsx` | [`src/renderer/src/components/onboarding/OnboardingInlineCommandTerminal.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/onboarding/OnboardingInlineCommandTerminal.tsx) |
| `OnboardingSkipConfirmationDialog.tsx` | [`src/renderer/src/components/onboarding/OnboardingSkipConfirmationDialog.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/onboarding/OnboardingSkipConfirmationDialog.tsx) |
| `OnboardingTourStep.tsx` | [`src/renderer/src/components/onboarding/OnboardingTourStep.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/onboarding/OnboardingTourStep.tsx) |
| `RepoStep.test.tsx` | [`src/renderer/src/components/onboarding/RepoStep.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/onboarding/RepoStep.test.tsx) |
| `RepoStep.tsx` | [`src/renderer/src/components/onboarding/RepoStep.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/onboarding/RepoStep.tsx) |
| `RepoStepNestedImportPanel.tsx` | [`src/renderer/src/components/onboarding/RepoStepNestedImportPanel.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/onboarding/RepoStepNestedImportPanel.tsx) |
| `ThemeStep.tsx` | [`src/renderer/src/components/onboarding/ThemeStep.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/onboarding/ThemeStep.tsx) |
| `WindowsTerminalStep.test.tsx` | [`src/renderer/src/components/onboarding/WindowsTerminalStep.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/onboarding/WindowsTerminalStep.test.tsx) |
| `WindowsTerminalStep.tsx` | [`src/renderer/src/components/onboarding/WindowsTerminalStep.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/onboarding/WindowsTerminalStep.tsx) |
| `theme-chrome-preview.tsx` | [`src/renderer/src/components/onboarding/theme-chrome-preview.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/onboarding/theme-chrome-preview.tsx) |
| `SetupGuideModal.tsx` | [`src/renderer/src/components/setup-guide/SetupGuideModal.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/setup-guide/SetupGuideModal.tsx) |
| `SetupGuideProgressRing.tsx` | [`src/renderer/src/components/setup-guide/SetupGuideProgressRing.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/setup-guide/SetupGuideProgressRing.tsx) |
| `SetupGuideTelemetryObserver.tsx` | [`src/renderer/src/components/setup-guide/SetupGuideTelemetryObserver.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/setup-guide/SetupGuideTelemetryObserver.tsx) |
| `StarNagAgentValueMomentObserver.test.tsx` | [`src/renderer/src/components/star-nag/StarNagAgentValueMomentObserver.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/star-nag/StarNagAgentValueMomentObserver.test.tsx) |
| `StarNagAgentValueMomentObserver.tsx` | [`src/renderer/src/components/star-nag/StarNagAgentValueMomentObserver.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/star-nag/StarNagAgentValueMomentObserver.tsx) |
| `StarNagToastHost.test.tsx` | [`src/renderer/src/components/star-nag/StarNagToastHost.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/star-nag/StarNagToastHost.test.tsx) |
| `StarNagToastHost.tsx` | [`src/renderer/src/components/star-nag/StarNagToastHost.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/star-nag/StarNagToastHost.tsx) |

## Desktop App - Dashboard, Stats & System Activity

*Total: 31 arquivos*

| Arquivo | Caminho Completo |
| :--- | :--- |
| `ActivityPrototypePage.tsx` | [`src/renderer/src/components/activity/ActivityPrototypePage.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/activity/ActivityPrototypePage.tsx) |
| `ActivityTitlebarControls.tsx` | [`src/renderer/src/components/activity/ActivityTitlebarControls.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/activity/ActivityTitlebarControls.tsx) |
| `DashboardAgentChildDisclosure.tsx` | [`src/renderer/src/components/dashboard/DashboardAgentChildDisclosure.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/dashboard/DashboardAgentChildDisclosure.tsx) |
| `DashboardAgentRow.test.tsx` | [`src/renderer/src/components/dashboard/DashboardAgentRow.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/dashboard/DashboardAgentRow.test.tsx) |
| `DashboardAgentRow.tsx` | [`src/renderer/src/components/dashboard/DashboardAgentRow.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/dashboard/DashboardAgentRow.tsx) |
| `DashboardAgentRowMessage.tsx` | [`src/renderer/src/components/dashboard/DashboardAgentRowMessage.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/dashboard/DashboardAgentRowMessage.tsx) |
| `DashboardAgentRowToolStep.tsx` | [`src/renderer/src/components/dashboard/DashboardAgentRowToolStep.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/dashboard/DashboardAgentRowToolStep.tsx) |
| `DashboardAgentRowTrailingControls.tsx` | [`src/renderer/src/components/dashboard/DashboardAgentRowTrailingControls.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/dashboard/DashboardAgentRowTrailingControls.tsx) |
| `RetainedAgentsSyncGate.tsx` | [`src/renderer/src/components/dashboard/RetainedAgentsSyncGate.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/dashboard/RetainedAgentsSyncGate.tsx) |
| `ClaudeUsageDailyChart.tsx` | [`src/renderer/src/components/stats/ClaudeUsageDailyChart.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/stats/ClaudeUsageDailyChart.tsx) |
| `ClaudeUsageDetails.tsx` | [`src/renderer/src/components/stats/ClaudeUsageDetails.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/stats/ClaudeUsageDetails.tsx) |
| `ClaudeUsageLoadingState.tsx` | [`src/renderer/src/components/stats/ClaudeUsageLoadingState.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/stats/ClaudeUsageLoadingState.tsx) |
| `ClaudeUsagePane.tsx` | [`src/renderer/src/components/stats/ClaudeUsagePane.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/stats/ClaudeUsagePane.tsx) |
| `ClaudeUsageRecentSessionsTable.tsx` | [`src/renderer/src/components/stats/ClaudeUsageRecentSessionsTable.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/stats/ClaudeUsageRecentSessionsTable.tsx) |
| `CodexUsageDailyChart.tsx` | [`src/renderer/src/components/stats/CodexUsageDailyChart.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/stats/CodexUsageDailyChart.tsx) |
| `CodexUsageDetails.tsx` | [`src/renderer/src/components/stats/CodexUsageDetails.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/stats/CodexUsageDetails.tsx) |
| `CodexUsagePane.tsx` | [`src/renderer/src/components/stats/CodexUsagePane.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/stats/CodexUsagePane.tsx) |
| `CodexUsageRecentSessionsTable.tsx` | [`src/renderer/src/components/stats/CodexUsageRecentSessionsTable.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/stats/CodexUsageRecentSessionsTable.tsx) |
| `OpenCodeUsageDetails.tsx` | [`src/renderer/src/components/stats/OpenCodeUsageDetails.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/stats/OpenCodeUsageDetails.tsx) |
| `OpenCodeUsagePane.tsx` | [`src/renderer/src/components/stats/OpenCodeUsagePane.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/stats/OpenCodeUsagePane.tsx) |
| `OpenCodeUsageRecentSessionsTable.tsx` | [`src/renderer/src/components/stats/OpenCodeUsageRecentSessionsTable.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/stats/OpenCodeUsageRecentSessionsTable.tsx) |
| `ShareUsageButton.tsx` | [`src/renderer/src/components/stats/ShareUsageButton.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/stats/ShareUsageButton.tsx) |
| `ShareUsageCard.tsx` | [`src/renderer/src/components/stats/ShareUsageCard.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/stats/ShareUsageCard.tsx) |
| `StatCard.tsx` | [`src/renderer/src/components/stats/StatCard.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/stats/StatCard.tsx) |
| `StatsPane.tsx` | [`src/renderer/src/components/stats/StatsPane.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/stats/StatsPane.tsx) |
| `UsageBreakdownSection.tsx` | [`src/renderer/src/components/stats/UsageBreakdownSection.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/stats/UsageBreakdownSection.tsx) |
| `UsageOverviewPane.tsx` | [`src/renderer/src/components/stats/UsageOverviewPane.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/stats/UsageOverviewPane.tsx) |
| `UsageSessionsTable.tsx` | [`src/renderer/src/components/stats/UsageSessionsTable.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/stats/UsageSessionsTable.tsx) |
| `share-card-utils.tsx` | [`src/renderer/src/components/stats/share-card-utils.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/stats/share-card-utils.tsx) |
| `usage-daily-chart.test.tsx` | [`src/renderer/src/components/stats/usage-daily-chart.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/stats/usage-daily-chart.test.tsx) |
| `usage-overview-sections.tsx` | [`src/renderer/src/components/stats/usage-overview-sections.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/stats/usage-overview-sections.tsx) |

## Desktop App - UI Primitives (Shadcn)

*Total: 32 arquivos*

| Arquivo | Caminho Completo |
| :--- | :--- |
| `accordion.tsx` | [`src/renderer/src/components/ui/accordion.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/ui/accordion.tsx) |
| `badge.tsx` | [`src/renderer/src/components/ui/badge.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/ui/badge.tsx) |
| `button-group.tsx` | [`src/renderer/src/components/ui/button-group.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/ui/button-group.tsx) |
| `button.tsx` | [`src/renderer/src/components/ui/button.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/ui/button.tsx) |
| `card.tsx` | [`src/renderer/src/components/ui/card.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/ui/card.tsx) |
| `checkbox.tsx` | [`src/renderer/src/components/ui/checkbox.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/ui/checkbox.tsx) |
| `collapsible.tsx` | [`src/renderer/src/components/ui/collapsible.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/ui/collapsible.tsx) |
| `color-picker.test.tsx` | [`src/renderer/src/components/ui/color-picker.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/ui/color-picker.test.tsx) |
| `color-picker.tsx` | [`src/renderer/src/components/ui/color-picker.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/ui/color-picker.tsx) |
| `command.tsx` | [`src/renderer/src/components/ui/command.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/ui/command.tsx) |
| `context-menu.tsx` | [`src/renderer/src/components/ui/context-menu.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/ui/context-menu.tsx) |
| `dialog.tsx` | [`src/renderer/src/components/ui/dialog.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/ui/dialog.tsx) |
| `dropdown-menu.tsx` | [`src/renderer/src/components/ui/dropdown-menu.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/ui/dropdown-menu.tsx) |
| `hover-card.tsx` | [`src/renderer/src/components/ui/hover-card.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/ui/hover-card.tsx) |
| `input.tsx` | [`src/renderer/src/components/ui/input.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/ui/input.tsx) |
| `label.tsx` | [`src/renderer/src/components/ui/label.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/ui/label.tsx) |
| `popover.test.tsx` | [`src/renderer/src/components/ui/popover.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/ui/popover.test.tsx) |
| `popover.tsx` | [`src/renderer/src/components/ui/popover.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/ui/popover.tsx) |
| `progress.tsx` | [`src/renderer/src/components/ui/progress.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/ui/progress.tsx) |
| `repo-multi-combobox.tsx` | [`src/renderer/src/components/ui/repo-multi-combobox.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/ui/repo-multi-combobox.tsx) |
| `scroll-area.test.tsx` | [`src/renderer/src/components/ui/scroll-area.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/ui/scroll-area.test.tsx) |
| `scroll-area.tsx` | [`src/renderer/src/components/ui/scroll-area.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/ui/scroll-area.tsx) |
| `select.tsx` | [`src/renderer/src/components/ui/select.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/ui/select.tsx) |
| `separator.tsx` | [`src/renderer/src/components/ui/separator.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/ui/separator.tsx) |
| `sheet.tsx` | [`src/renderer/src/components/ui/sheet.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/ui/sheet.tsx) |
| `slider.tsx` | [`src/renderer/src/components/ui/slider.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/ui/slider.tsx) |
| `sonner.tsx` | [`src/renderer/src/components/ui/sonner.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/ui/sonner.tsx) |
| `tabs.tsx` | [`src/renderer/src/components/ui/tabs.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/ui/tabs.tsx) |
| `team-multi-combobox.tsx` | [`src/renderer/src/components/ui/team-multi-combobox.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/ui/team-multi-combobox.tsx) |
| `toggle-group.tsx` | [`src/renderer/src/components/ui/toggle-group.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/ui/toggle-group.tsx) |
| `toggle.tsx` | [`src/renderer/src/components/ui/toggle.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/ui/toggle.tsx) |
| `tooltip.tsx` | [`src/renderer/src/components/ui/tooltip.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/ui/tooltip.tsx) |

## Desktop App - Shared & Miscellaneous Components

*Total: 60 arquivos*

| Arquivo | Caminho Completo |
| :--- | :--- |
| `AgentHibernationGate.tsx` | [`src/renderer/src/components/AgentHibernationGate.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/AgentHibernationGate.tsx) |
| `AgentStateDot.tsx` | [`src/renderer/src/components/AgentStateDot.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/AgentStateDot.tsx) |
| `CodexRestartChip.tsx` | [`src/renderer/src/components/CodexRestartChip.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/CodexRestartChip.tsx) |
| `DetachedHeadBadge.tsx` | [`src/renderer/src/components/DetachedHeadBadge.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/DetachedHeadBadge.tsx) |
| `FirstLaunchBanner.tsx` | [`src/renderer/src/components/FirstLaunchBanner.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/FirstLaunchBanner.tsx) |
| `GitHubItemDialog.tsx` | [`src/renderer/src/components/GitHubItemDialog.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/GitHubItemDialog.tsx) |
| `GitLabItemDialog.tsx` | [`src/renderer/src/components/GitLabItemDialog.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/GitLabItemDialog.tsx) |
| `JiraIssueWorkspace.tsx` | [`src/renderer/src/components/JiraIssueWorkspace.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/JiraIssueWorkspace.tsx) |
| `Landing.tsx` | [`src/renderer/src/components/Landing.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/Landing.tsx) |
| `LinearIssueMarkdownDescriptionEditor.tsx` | [`src/renderer/src/components/LinearIssueMarkdownDescriptionEditor.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/LinearIssueMarkdownDescriptionEditor.tsx) |
| `LinearIssueMarkdownToolbar.tsx` | [`src/renderer/src/components/LinearIssueMarkdownToolbar.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/LinearIssueMarkdownToolbar.tsx) |
| `LinearIssueTextEditor.tsx` | [`src/renderer/src/components/LinearIssueTextEditor.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/LinearIssueTextEditor.tsx) |
| `LinearIssueWorkspace.tsx` | [`src/renderer/src/components/LinearIssueWorkspace.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/LinearIssueWorkspace.tsx) |
| `LinearItemDrawer.tsx` | [`src/renderer/src/components/LinearItemDrawer.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/LinearItemDrawer.tsx) |
| `NewWorkspaceComposerCard.test.tsx` | [`src/renderer/src/components/NewWorkspaceComposerCard.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/NewWorkspaceComposerCard.test.tsx) |
| `NewWorkspaceComposerCard.tsx` | [`src/renderer/src/components/NewWorkspaceComposerCard.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/NewWorkspaceComposerCard.tsx) |
| `NewWorkspaceComposerModal.tsx` | [`src/renderer/src/components/NewWorkspaceComposerModal.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/NewWorkspaceComposerModal.tsx) |
| `PullRequestPage.tsx` | [`src/renderer/src/components/PullRequestPage.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/PullRequestPage.tsx) |
| `QuickOpen.tsx` | [`src/renderer/src/components/QuickOpen.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/QuickOpen.tsx) |
| `SelectedTextCopyMenu.tsx` | [`src/renderer/src/components/SelectedTextCopyMenu.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/SelectedTextCopyMenu.tsx) |
| `ShortcutKeyCombo.tsx` | [`src/renderer/src/components/ShortcutKeyCombo.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/ShortcutKeyCombo.tsx) |
| `Sidebar.tsx` | [`src/renderer/src/components/Sidebar.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/Sidebar.tsx) |
| `StarNagCard.test.tsx` | [`src/renderer/src/components/StarNagCard.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/StarNagCard.test.tsx) |
| `StarNagCard.tsx` | [`src/renderer/src/components/StarNagCard.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/StarNagCard.tsx) |
| `TaskPage.tsx` | [`src/renderer/src/components/TaskPage.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/TaskPage.tsx) |
| `TelemetryFirstLaunchSurface.tsx` | [`src/renderer/src/components/TelemetryFirstLaunchSurface.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/TelemetryFirstLaunchSurface.tsx) |
| `Terminal.tsx` | [`src/renderer/src/components/Terminal.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/Terminal.tsx) |
| `TerminalSearch.tsx` | [`src/renderer/src/components/TerminalSearch.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/TerminalSearch.tsx) |
| `UpdateCard.tsx` | [`src/renderer/src/components/UpdateCard.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/UpdateCard.tsx) |
| `WorktreeJumpPalette.tsx` | [`src/renderer/src/components/WorktreeJumpPalette.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/WorktreeJumpPalette.tsx) |
| `ZoomOverlay.tsx` | [`src/renderer/src/components/ZoomOverlay.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/ZoomOverlay.tsx) |
| `confirmation-dialog.tsx` | [`src/renderer/src/components/confirmation-dialog.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/confirmation-dialog.tsx) |
| `CrashReportDialog.tsx` | [`src/renderer/src/components/crash-report/CrashReportDialog.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/crash-report/CrashReportDialog.tsx) |
| `CrashReportDialogSurface.tsx` | [`src/renderer/src/components/crash-report/CrashReportDialogSurface.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/crash-report/CrashReportDialogSurface.tsx) |
| `DictationController.tsx` | [`src/renderer/src/components/dictation/DictationController.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/dictation/DictationController.tsx) |
| `DictationIndicator.tsx` | [`src/renderer/src/components/dictation/DictationIndicator.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/dictation/DictationIndicator.tsx) |
| `use-hold-dictation-gesture.test.tsx` | [`src/renderer/src/components/dictation/use-hold-dictation-gesture.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/dictation/use-hold-dictation-gesture.test.tsx) |
| `RecoverableRenderErrorBoundary.lazy-chunk.test.tsx` | [`src/renderer/src/components/error-boundaries/RecoverableRenderErrorBoundary.lazy-chunk.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/error-boundaries/RecoverableRenderErrorBoundary.lazy-chunk.test.tsx) |
| `RecoverableRenderErrorBoundary.tsx` | [`src/renderer/src/components/error-boundaries/RecoverableRenderErrorBoundary.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/error-boundaries/RecoverableRenderErrorBoundary.tsx) |
| `JiraIcon.tsx` | [`src/renderer/src/components/icons/JiraIcon.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/icons/JiraIcon.tsx) |
| `LinearIcon.tsx` | [`src/renderer/src/components/icons/LinearIcon.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/icons/LinearIcon.tsx) |
| `WarpIcon.tsx` | [`src/renderer/src/components/icons/WarpIcon.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/icons/WarpIcon.tsx) |
| `integration-status-pill.tsx` | [`src/renderer/src/components/integration-status-pill.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/integration-status-pill.tsx) |
| `jira-connect-dialog.tsx` | [`src/renderer/src/components/jira-connect-dialog.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/jira-connect-dialog.tsx) |
| `linear-api-key-dialog.tsx` | [`src/renderer/src/components/linear-api-key-dialog.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/linear-api-key-dialog.tsx) |
| `linear-priority-icon.tsx` | [`src/renderer/src/components/linear-priority-icon.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/linear-priority-icon.tsx) |
| `linear-project-view-surfaces.tsx` | [`src/renderer/src/components/linear-project-view-surfaces.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/linear-project-view-surfaces.tsx) |
| `linear-scope-selector.tsx` | [`src/renderer/src/components/linear-scope-selector.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/linear-scope-selector.tsx) |
| `link-routing-preference-dialog.tsx` | [`src/renderer/src/components/link-routing-preference-dialog.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/link-routing-preference-dialog.tsx) |
| `NestedRepoChecklist.test.tsx` | [`src/renderer/src/components/repo/NestedRepoChecklist.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/repo/NestedRepoChecklist.test.tsx) |
| `NestedRepoChecklist.tsx` | [`src/renderer/src/components/repo/NestedRepoChecklist.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/repo/NestedRepoChecklist.tsx) |
| `NestedRepoScanLimitNotice.tsx` | [`src/renderer/src/components/repo/NestedRepoScanLimitNotice.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/repo/NestedRepoScanLimitNotice.tsx) |
| `RepoBadgeLabel.tsx` | [`src/renderer/src/components/repo/RepoBadgeLabel.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/repo/RepoBadgeLabel.tsx) |
| `RepoCombobox.tsx` | [`src/renderer/src/components/repo/RepoCombobox.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/repo/RepoCombobox.tsx) |
| `repo-fork-indicator.tsx` | [`src/renderer/src/components/repo/repo-fork-indicator.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/repo/repo-fork-indicator.tsx) |
| `repo-icon.tsx` | [`src/renderer/src/components/repo/repo-icon.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/repo/repo-icon.tsx) |
| `useDaemonActions.tsx` | [`src/renderer/src/components/shared/useDaemonActions.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/shared/useDaemonActions.tsx) |
| `task-page-github-work-item-status-badge.tsx` | [`src/renderer/src/components/task-page-github-work-item-status-badge.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/task-page-github-work-item-status-badge.tsx) |
| `task-page-localized-options.tsx` | [`src/renderer/src/components/task-page-localized-options.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/task-page-localized-options.tsx) |
| `task-project-source-combobox.tsx` | [`src/renderer/src/components/task-project-source-combobox.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/components/task-project-source-combobox.tsx) |

## Mobile App - Pages & Routes

*Total: 22 arquivos*

| Arquivo | Caminho Completo |
| :--- | :--- |
| `_layout.tsx` | [`mobile/app/_layout.tsx`](file:///C:/Users/fjuni/orca/mobile/app/_layout.tsx) |
| `about.tsx` | [`mobile/app/about.tsx`](file:///C:/Users/fjuni/orca/mobile/app/about.tsx) |
| `browser-settings.tsx` | [`mobile/app/browser-settings.tsx`](file:///C:/Users/fjuni/orca/mobile/app/browser-settings.tsx) |
| `accounts.tsx` | [`mobile/app/h/[hostId]/accounts.tsx`](file:///C:/Users/fjuni/orca/mobile/app/h/[hostId]/accounts.tsx) |
| `[worktreeId].tsx` | [`mobile/app/h/[hostId]/files/[worktreeId].tsx`](file:///C:/Users/fjuni/orca/mobile/app/h/[hostId]/files/[worktreeId].tsx) |
| `[worktreeId].tsx` | [`mobile/app/h/[hostId]/history/[worktreeId].tsx`](file:///C:/Users/fjuni/orca/mobile/app/h/[hostId]/history/[worktreeId].tsx) |
| `index.tsx` | [`mobile/app/h/[hostId]/index.tsx`](file:///C:/Users/fjuni/orca/mobile/app/h/[hostId]/index.tsx) |
| `[worktreeId].tsx` | [`mobile/app/h/[hostId]/pr/[worktreeId].tsx`](file:///C:/Users/fjuni/orca/mobile/app/h/[hostId]/pr/[worktreeId].tsx) |
| `[worktreeId].tsx` | [`mobile/app/h/[hostId]/review/[worktreeId].tsx`](file:///C:/Users/fjuni/orca/mobile/app/h/[hostId]/review/[worktreeId].tsx) |
| `[worktreeId].tsx` | [`mobile/app/h/[hostId]/session/[worktreeId].tsx`](file:///C:/Users/fjuni/orca/mobile/app/h/[hostId]/session/[worktreeId].tsx) |
| `[worktreeId].tsx` | [`mobile/app/h/[hostId]/source-control/[worktreeId].tsx`](file:///C:/Users/fjuni/orca/mobile/app/h/[hostId]/source-control/[worktreeId].tsx) |
| `tasks.tsx` | [`mobile/app/h/[hostId]/tasks.tsx`](file:///C:/Users/fjuni/orca/mobile/app/h/[hostId]/tasks.tsx) |
| `_layout.tsx` | [`mobile/app/h/_layout.tsx`](file:///C:/Users/fjuni/orca/mobile/app/h/_layout.tsx) |
| `index.tsx` | [`mobile/app/index.tsx`](file:///C:/Users/fjuni/orca/mobile/app/index.tsx) |
| `notifications.tsx` | [`mobile/app/notifications.tsx`](file:///C:/Users/fjuni/orca/mobile/app/notifications.tsx) |
| `pair-confirm.tsx` | [`mobile/app/pair-confirm.tsx`](file:///C:/Users/fjuni/orca/mobile/app/pair-confirm.tsx) |
| `pair-scan.tsx` | [`mobile/app/pair-scan.tsx`](file:///C:/Users/fjuni/orca/mobile/app/pair-scan.tsx) |
| `pair.tsx` | [`mobile/app/pair.tsx`](file:///C:/Users/fjuni/orca/mobile/app/pair.tsx) |
| `settings.tsx` | [`mobile/app/settings.tsx`](file:///C:/Users/fjuni/orca/mobile/app/settings.tsx) |
| `terminal-settings.tsx` | [`mobile/app/terminal-settings.tsx`](file:///C:/Users/fjuni/orca/mobile/app/terminal-settings.tsx) |
| `troubleshoot.tsx` | [`mobile/app/troubleshoot.tsx`](file:///C:/Users/fjuni/orca/mobile/app/troubleshoot.tsx) |
| `voice-settings.tsx` | [`mobile/app/voice-settings.tsx`](file:///C:/Users/fjuni/orca/mobile/app/voice-settings.tsx) |

## Mobile App - UI Components & Features

*Total: 80 arquivos*

| Arquivo | Caminho Completo |
| :--- | :--- |
| `MobileBrowserKeyRow.tsx` | [`mobile/src/browser/MobileBrowserKeyRow.tsx`](file:///C:/Users/fjuni/orca/mobile/src/browser/MobileBrowserKeyRow.tsx) |
| `MobileBrowserPane.tsx` | [`mobile/src/browser/MobileBrowserPane.tsx`](file:///C:/Users/fjuni/orca/mobile/src/browser/MobileBrowserPane.tsx) |
| `MobileBrowserPointerModifiers.tsx` | [`mobile/src/browser/MobileBrowserPointerModifiers.tsx`](file:///C:/Users/fjuni/orca/mobile/src/browser/MobileBrowserPointerModifiers.tsx) |
| `MobileBrowserToolbarIconButton.tsx` | [`mobile/src/browser/MobileBrowserToolbarIconButton.tsx`](file:///C:/Users/fjuni/orca/mobile/src/browser/MobileBrowserToolbarIconButton.tsx) |
| `MobileBrowserViewModeSwitch.tsx` | [`mobile/src/browser/MobileBrowserViewModeSwitch.tsx`](file:///C:/Users/fjuni/orca/mobile/src/browser/MobileBrowserViewModeSwitch.tsx) |
| `AccountUsage.tsx` | [`mobile/src/components/AccountUsage.tsx`](file:///C:/Users/fjuni/orca/mobile/src/components/AccountUsage.tsx) |
| `ActionSheetModal.tsx` | [`mobile/src/components/ActionSheetModal.tsx`](file:///C:/Users/fjuni/orca/mobile/src/components/ActionSheetModal.tsx) |
| `AgentIcons.tsx` | [`mobile/src/components/AgentIcons.tsx`](file:///C:/Users/fjuni/orca/mobile/src/components/AgentIcons.tsx) |
| `AgentSpinner.tsx` | [`mobile/src/components/AgentSpinner.tsx`](file:///C:/Users/fjuni/orca/mobile/src/components/AgentSpinner.tsx) |
| `AgentStateDot.tsx` | [`mobile/src/components/AgentStateDot.tsx`](file:///C:/Users/fjuni/orca/mobile/src/components/AgentStateDot.tsx) |
| `AuthFailedBanner.tsx` | [`mobile/src/components/AuthFailedBanner.tsx`](file:///C:/Users/fjuni/orca/mobile/src/components/AuthFailedBanner.tsx) |
| `BottomDrawer.tsx` | [`mobile/src/components/BottomDrawer.tsx`](file:///C:/Users/fjuni/orca/mobile/src/components/BottomDrawer.tsx) |
| `ConfirmModal.tsx` | [`mobile/src/components/ConfirmModal.tsx`](file:///C:/Users/fjuni/orca/mobile/src/components/ConfirmModal.tsx) |
| `ConnectionLog.tsx` | [`mobile/src/components/ConnectionLog.tsx`](file:///C:/Users/fjuni/orca/mobile/src/components/ConnectionLog.tsx) |
| `CustomKeyModal.tsx` | [`mobile/src/components/CustomKeyModal.tsx`](file:///C:/Users/fjuni/orca/mobile/src/components/CustomKeyModal.tsx) |
| `DragReorderList.tsx` | [`mobile/src/components/DragReorderList.tsx`](file:///C:/Users/fjuni/orca/mobile/src/components/DragReorderList.tsx) |
| `MobileAgentIcon.tsx` | [`mobile/src/components/MobileAgentIcon.tsx`](file:///C:/Users/fjuni/orca/mobile/src/components/MobileAgentIcon.tsx) |
| `MobileDictationSetupSheet.tsx` | [`mobile/src/components/MobileDictationSetupSheet.tsx`](file:///C:/Users/fjuni/orca/mobile/src/components/MobileDictationSetupSheet.tsx) |
| `MobileDiffReviewBody.tsx` | [`mobile/src/components/MobileDiffReviewBody.tsx`](file:///C:/Users/fjuni/orca/mobile/src/components/MobileDiffReviewBody.tsx) |
| `MobileDiffReviewDrawers.tsx` | [`mobile/src/components/MobileDiffReviewDrawers.tsx`](file:///C:/Users/fjuni/orca/mobile/src/components/MobileDiffReviewDrawers.tsx) |
| `MobileDiffReviewFileSummary.tsx` | [`mobile/src/components/MobileDiffReviewFileSummary.tsx`](file:///C:/Users/fjuni/orca/mobile/src/components/MobileDiffReviewFileSummary.tsx) |
| `MobileDiffReviewFooter.tsx` | [`mobile/src/components/MobileDiffReviewFooter.tsx`](file:///C:/Users/fjuni/orca/mobile/src/components/MobileDiffReviewFooter.tsx) |
| `MobileDiffReviewHeader.tsx` | [`mobile/src/components/MobileDiffReviewHeader.tsx`](file:///C:/Users/fjuni/orca/mobile/src/components/MobileDiffReviewHeader.tsx) |
| `MobileDiffReviewLine.tsx` | [`mobile/src/components/MobileDiffReviewLine.tsx`](file:///C:/Users/fjuni/orca/mobile/src/components/MobileDiffReviewLine.tsx) |
| `MobileDiffReviewScreenView.tsx` | [`mobile/src/components/MobileDiffReviewScreenView.tsx`](file:///C:/Users/fjuni/orca/mobile/src/components/MobileDiffReviewScreenView.tsx) |
| `MobileHtmlPreview.tsx` | [`mobile/src/components/MobileHtmlPreview.tsx`](file:///C:/Users/fjuni/orca/mobile/src/components/MobileHtmlPreview.tsx) |
| `MobileMarkdown.tsx` | [`mobile/src/components/MobileMarkdown.tsx`](file:///C:/Users/fjuni/orca/mobile/src/components/MobileMarkdown.tsx) |
| `MobilePRSidebar.tsx` | [`mobile/src/components/MobilePRSidebar.tsx`](file:///C:/Users/fjuni/orca/mobile/src/components/MobilePRSidebar.tsx) |
| `MobilePrBasePicker.tsx` | [`mobile/src/components/MobilePrBasePicker.tsx`](file:///C:/Users/fjuni/orca/mobile/src/components/MobilePrBasePicker.tsx) |
| `MobilePrComposeSheet.tsx` | [`mobile/src/components/MobilePrComposeSheet.tsx`](file:///C:/Users/fjuni/orca/mobile/src/components/MobilePrComposeSheet.tsx) |
| `MobileRepoIcon.tsx` | [`mobile/src/components/MobileRepoIcon.tsx`](file:///C:/Users/fjuni/orca/mobile/src/components/MobileRepoIcon.tsx) |
| `MobileRichMarkdownEditor.tsx` | [`mobile/src/components/MobileRichMarkdownEditor.tsx`](file:///C:/Users/fjuni/orca/mobile/src/components/MobileRichMarkdownEditor.tsx) |
| `MobileSyntaxSegments.tsx` | [`mobile/src/components/MobileSyntaxSegments.tsx`](file:///C:/Users/fjuni/orca/mobile/src/components/MobileSyntaxSegments.tsx) |
| `MobileWorkspaceNameInput.tsx` | [`mobile/src/components/MobileWorkspaceNameInput.tsx`](file:///C:/Users/fjuni/orca/mobile/src/components/MobileWorkspaceNameInput.tsx) |
| `NewWorktreeModal.tsx` | [`mobile/src/components/NewWorktreeModal.tsx`](file:///C:/Users/fjuni/orca/mobile/src/components/NewWorktreeModal.tsx) |
| `NewWorktreeModalController.tsx` | [`mobile/src/components/NewWorktreeModalController.tsx`](file:///C:/Users/fjuni/orca/mobile/src/components/NewWorktreeModalController.tsx) |
| `OrcaLogo.tsx` | [`mobile/src/components/OrcaLogo.tsx`](file:///C:/Users/fjuni/orca/mobile/src/components/OrcaLogo.tsx) |
| `PickerListDrawer.tsx` | [`mobile/src/components/PickerListDrawer.tsx`](file:///C:/Users/fjuni/orca/mobile/src/components/PickerListDrawer.tsx) |
| `PickerModal.tsx` | [`mobile/src/components/PickerModal.tsx`](file:///C:/Users/fjuni/orca/mobile/src/components/PickerModal.tsx) |
| `ProtocolBlockScreen.tsx` | [`mobile/src/components/ProtocolBlockScreen.tsx`](file:///C:/Users/fjuni/orca/mobile/src/components/ProtocolBlockScreen.tsx) |
| `RightDrawer.tsx` | [`mobile/src/components/RightDrawer.tsx`](file:///C:/Users/fjuni/orca/mobile/src/components/RightDrawer.tsx) |
| `StatusDot.tsx` | [`mobile/src/components/StatusDot.tsx`](file:///C:/Users/fjuni/orca/mobile/src/components/StatusDot.tsx) |
| `TaskProviderLogo.tsx` | [`mobile/src/components/TaskProviderLogo.tsx`](file:///C:/Users/fjuni/orca/mobile/src/components/TaskProviderLogo.tsx) |
| `TerminalShortcutSettings.tsx` | [`mobile/src/components/TerminalShortcutSettings.tsx`](file:///C:/Users/fjuni/orca/mobile/src/components/TerminalShortcutSettings.tsx) |
| `TextInputModal.tsx` | [`mobile/src/components/TextInputModal.tsx`](file:///C:/Users/fjuni/orca/mobile/src/components/TextInputModal.tsx) |
| `VoiceModelList.tsx` | [`mobile/src/components/VoiceModelList.tsx`](file:///C:/Users/fjuni/orca/mobile/src/components/VoiceModelList.tsx) |
| `WorkspaceDetailPlaceholder.tsx` | [`mobile/src/components/WorkspaceDetailPlaceholder.tsx`](file:///C:/Users/fjuni/orca/mobile/src/components/WorkspaceDetailPlaceholder.tsx) |
| `WorktreeAgentList.tsx` | [`mobile/src/components/WorktreeAgentList.tsx`](file:///C:/Users/fjuni/orca/mobile/src/components/WorktreeAgentList.tsx) |
| `WorktreeAgentRow.tsx` | [`mobile/src/components/WorktreeAgentRow.tsx`](file:///C:/Users/fjuni/orca/mobile/src/components/WorktreeAgentRow.tsx) |
| `WorktreeListRow.tsx` | [`mobile/src/components/WorktreeListRow.tsx`](file:///C:/Users/fjuni/orca/mobile/src/components/WorktreeListRow.tsx) |
| `WorktreeMetaGlyphs.tsx` | [`mobile/src/components/WorktreeMetaGlyphs.tsx`](file:///C:/Users/fjuni/orca/mobile/src/components/WorktreeMetaGlyphs.tsx) |
| `CommentMarkdown.tsx` | [`mobile/src/components/pr-sidebar/CommentMarkdown.tsx`](file:///C:/Users/fjuni/orca/mobile/src/components/pr-sidebar/CommentMarkdown.tsx) |
| `MermaidDiagram.tsx` | [`mobile/src/components/pr-sidebar/MermaidDiagram.tsx`](file:///C:/Users/fjuni/orca/mobile/src/components/pr-sidebar/MermaidDiagram.tsx) |
| `MobileLinkPrForm.tsx` | [`mobile/src/components/pr-sidebar/MobileLinkPrForm.tsx`](file:///C:/Users/fjuni/orca/mobile/src/components/pr-sidebar/MobileLinkPrForm.tsx) |
| `MobilePrComposeForm.tsx` | [`mobile/src/components/pr-sidebar/MobilePrComposeForm.tsx`](file:///C:/Users/fjuni/orca/mobile/src/components/pr-sidebar/MobilePrComposeForm.tsx) |
| `MobilePrViewPanel.tsx` | [`mobile/src/components/pr-sidebar/MobilePrViewPanel.tsx`](file:///C:/Users/fjuni/orca/mobile/src/components/pr-sidebar/MobilePrViewPanel.tsx) |
| `PRActionsSection.tsx` | [`mobile/src/components/pr-sidebar/PRActionsSection.tsx`](file:///C:/Users/fjuni/orca/mobile/src/components/pr-sidebar/PRActionsSection.tsx) |
| `PRCheckDetail.tsx` | [`mobile/src/components/pr-sidebar/PRCheckDetail.tsx`](file:///C:/Users/fjuni/orca/mobile/src/components/pr-sidebar/PRCheckDetail.tsx) |
| `PRChecksSection.tsx` | [`mobile/src/components/pr-sidebar/PRChecksSection.tsx`](file:///C:/Users/fjuni/orca/mobile/src/components/pr-sidebar/PRChecksSection.tsx) |
| `PRCommentCard.tsx` | [`mobile/src/components/pr-sidebar/PRCommentCard.tsx`](file:///C:/Users/fjuni/orca/mobile/src/components/pr-sidebar/PRCommentCard.tsx) |
| `PRCommentComposer.tsx` | [`mobile/src/components/pr-sidebar/PRCommentComposer.tsx`](file:///C:/Users/fjuni/orca/mobile/src/components/pr-sidebar/PRCommentComposer.tsx) |
| `PRCommentsSection.tsx` | [`mobile/src/components/pr-sidebar/PRCommentsSection.tsx`](file:///C:/Users/fjuni/orca/mobile/src/components/pr-sidebar/PRCommentsSection.tsx) |
| `PRConflictingFilesSection.tsx` | [`mobile/src/components/pr-sidebar/PRConflictingFilesSection.tsx`](file:///C:/Users/fjuni/orca/mobile/src/components/pr-sidebar/PRConflictingFilesSection.tsx) |
| `PRReviewersSection.tsx` | [`mobile/src/components/pr-sidebar/PRReviewersSection.tsx`](file:///C:/Users/fjuni/orca/mobile/src/components/pr-sidebar/PRReviewersSection.tsx) |
| `PRSection.tsx` | [`mobile/src/components/pr-sidebar/PRSection.tsx`](file:///C:/Users/fjuni/orca/mobile/src/components/pr-sidebar/PRSection.tsx) |
| `PRSidebarHeader.tsx` | [`mobile/src/components/pr-sidebar/PRSidebarHeader.tsx`](file:///C:/Users/fjuni/orca/mobile/src/components/pr-sidebar/PRSidebarHeader.tsx) |
| `PrSidebarCreateEmptyState.tsx` | [`mobile/src/components/pr-sidebar/PrSidebarCreateEmptyState.tsx`](file:///C:/Users/fjuni/orca/mobile/src/components/pr-sidebar/PrSidebarCreateEmptyState.tsx) |
| `ReviewerPickerDrawer.tsx` | [`mobile/src/components/pr-sidebar/ReviewerPickerDrawer.tsx`](file:///C:/Users/fjuni/orca/mobile/src/components/pr-sidebar/ReviewerPickerDrawer.tsx) |
| `MobileFileExplorerPanel.tsx` | [`mobile/src/files/MobileFileExplorerPanel.tsx`](file:///C:/Users/fjuni/orca/mobile/src/files/MobileFileExplorerPanel.tsx) |
| `SessionDockColumn.tsx` | [`mobile/src/session/SessionDockColumn.tsx`](file:///C:/Users/fjuni/orca/mobile/src/session/SessionDockColumn.tsx) |
| `TerminalPaneView.tsx` | [`mobile/src/session/TerminalPaneView.tsx`](file:///C:/Users/fjuni/orca/mobile/src/session/TerminalPaneView.tsx) |
| `MobileBranchDiffPreviewDrawer.tsx` | [`mobile/src/source-control/MobileBranchDiffPreviewDrawer.tsx`](file:///C:/Users/fjuni/orca/mobile/src/source-control/MobileBranchDiffPreviewDrawer.tsx) |
| `MobileSourceControlContent.tsx` | [`mobile/src/source-control/MobileSourceControlContent.tsx`](file:///C:/Users/fjuni/orca/mobile/src/source-control/MobileSourceControlContent.tsx) |
| `MobileSourceControlFileRows.tsx` | [`mobile/src/source-control/MobileSourceControlFileRows.tsx`](file:///C:/Users/fjuni/orca/mobile/src/source-control/MobileSourceControlFileRows.tsx) |
| `MobileSourceControlHeader.tsx` | [`mobile/src/source-control/MobileSourceControlHeader.tsx`](file:///C:/Users/fjuni/orca/mobile/src/source-control/MobileSourceControlHeader.tsx) |
| `MobileSourceControlModals.tsx` | [`mobile/src/source-control/MobileSourceControlModals.tsx`](file:///C:/Users/fjuni/orca/mobile/src/source-control/MobileSourceControlModals.tsx) |
| `MobileSourceControlPanel.tsx` | [`mobile/src/source-control/MobileSourceControlPanel.tsx`](file:///C:/Users/fjuni/orca/mobile/src/source-control/MobileSourceControlPanel.tsx) |
| `mobile-source-control-review-entry.tsx` | [`mobile/src/source-control/mobile-source-control-review-entry.tsx`](file:///C:/Users/fjuni/orca/mobile/src/source-control/mobile-source-control-review-entry.tsx) |
| `TerminalWebView.tsx` | [`mobile/src/terminal/TerminalWebView.tsx`](file:///C:/Users/fjuni/orca/mobile/src/terminal/TerminalWebView.tsx) |
| `client-context.tsx` | [`mobile/src/transport/client-context.tsx`](file:///C:/Users/fjuni/orca/mobile/src/transport/client-context.tsx) |

## Miscellaneous / Other

*Total: 13 arquivos*

| Arquivo | Caminho Completo |
| :--- | :--- |
| `useAppMenuPaste.test.tsx` | [`src/renderer/src/hooks/useAppMenuPaste.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/hooks/useAppMenuPaste.test.tsx) |
| `useDetectedAgents.test.tsx` | [`src/renderer/src/hooks/useDetectedAgents.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/hooks/useDetectedAgents.test.tsx) |
| `useGitHubSlugMetadata.test.tsx` | [`src/renderer/src/hooks/useGitHubSlugMetadata.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/hooks/useGitHubSlugMetadata.test.tsx) |
| `useInstalledAgentSkills.react.test.tsx` | [`src/renderer/src/hooks/useInstalledAgentSkills.react.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/hooks/useInstalledAgentSkills.react.test.tsx) |
| `useModalReturnFocus.test.tsx` | [`src/renderer/src/hooks/useModalReturnFocus.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/hooks/useModalReturnFocus.test.tsx) |
| `usePrimarySelectionPaste.test.tsx` | [`src/renderer/src/hooks/usePrimarySelectionPaste.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/hooks/usePrimarySelectionPaste.test.tsx) |
| `I18nProvider.tsx` | [`src/renderer/src/i18n/I18nProvider.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/i18n/I18nProvider.tsx) |
| `agent-catalog.tsx` | [`src/renderer/src/lib/agent-catalog.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/lib/agent-catalog.tsx) |
| `agent-icon-glyphs.tsx` | [`src/renderer/src/lib/agent-icon-glyphs.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/lib/agent-icon-glyphs.tsx) |
| `open-in-app-catalog.tsx` | [`src/renderer/src/lib/open-in-app-catalog.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/lib/open-in-app-catalog.tsx) |
| `terminal-shortcut-capture-notification.test.tsx` | [`src/renderer/src/lib/terminal-shortcut-capture-notification.test.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/lib/terminal-shortcut-capture-notification.test.tsx) |
| `terminal-shortcut-capture-notification.tsx` | [`src/renderer/src/lib/terminal-shortcut-capture-notification.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/lib/terminal-shortcut-capture-notification.tsx) |
| `WebConnect.tsx` | [`src/renderer/src/web/WebConnect.tsx`](file:///C:/Users/fjuni/orca/src/renderer/src/web/WebConnect.tsx) |

