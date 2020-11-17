# Logic App to trigger Policy Remediation at Management Group

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fdimilider%2FAzure%2Fmaster%2FLogicApps%2FTriggerPolicyRemediation%2Fdeploy.json" target="_blank">
  <img src="https://aka.ms/deploytoazurebutton"/>
</a>

This Logic App will be triggered by recurring scheduler to trigger policy remediation on your noncompliant DeployIfNotExists policies. 

> **_NOTE:_**  Please make sure to provide at least the "Resource Policy Contributor" RBAC role for the System Managed Identity of the Logic App on the Management Group scope where your policy-(set) is assigned. 