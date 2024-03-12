# AI-IaC-Prompts
Give your feedback or thoughts on what prompts you would like to see improved by the Azure Deployments team.

## Submitting a prompt
Create a new issue by using the provided "feature request" template. Please ensure that you have checked for any duplicate issues before creating the issue. If you are inserting a prompt with sensitive data, make sure to redact any private info before creating your issue.

### **IMPORTANT** What's a good prompt to submit to this forum? 
For the purposes of this forum, a good prompt meets the following criteria:
- Can be run in Copilot with a specific expected result
- Specific resource types should be involved at some point contextually. This can be explicit (i.e. create a VM), or implicit (i.e. create a three-tiered application)
- Expected result is generic enough to apply to other customers. While specific prompts are necessary for personal Copilot use, they will likely be unapplicable to others and thus deprioritized. Improving a generic variation of the specific prompt will improve the specific output.
- Action required is not trivial (user could not easily accomplish on their own)
- Prompt is relevant to IaC

Examples of good prompts:
- Help me set up a three-tiered application
- Create a role assignment with read permissions for my resource group "good-example-rg" (specific RG name is ok)
- Help upgrade this existing code tied to vX.XX to vX.XX

Examples of bad prompts:
- Deploy for me X resources in my resource group "bad-example-rg" (too generic, no specific resource types)
- Add a tag to a resource (trivial action)
- Check the status of my VM (would not use IaC)
- Deploy for me three VMs named "joe" "jill" and "jack", two virtual networks named "nate" and "natalie", one AKS cluster named "cluster1", and five storage accounts "one" "two "three" "four" and "five" under resource group "bad-example-rg" (overly specific/wordy and thus unlikely to apply to others, could be made good with generalization)

## Disclaimers
The Azure Deployments team does NOT guarantee that they will make submitted prompts work with full confidence or functionality. Input will be taken to help make best efforts to improve your Copilot IaC experience. Issues will be closed when the team deems that the best effort has been made.
