# Microsoft-Entra-ID-MFA-&-Condtional-Access-Policies

## Objective

The MFA & conditional access project is to protect an organization while also providing the right levels of access to users who need it. The primary focus was to establish a custom conditional access policy that enabled MFA for users within a selected group.
While Microsoft Entra ID has policy templates, I used a custom policy to get more hands-on experience.
### Skills Learned

- Understanding of conditional access signals.
- Implementation of regulatory compliance and access policies.
- Implementation of zero-trust framework.
- Knowledge of authentication methods such as passwordless and token-based.
- Development of active directory administration.

### Tools Used

- Microsoft Entra ID.
- Microsoft Entra ID Premium P1 license (required for conditional access).

## Steps

*Ref 1: Create a new test user and add the user to the test group*
<img src="https://github.com/dnalegri/Entra-MFA/assets/164395911/57b81e31-45d0-4230-bbde-f734d4e212fe" />

*Ref 2: Navigate to the Microsoft Entra ID side panel and select conditional access, then click Create New Policy*
<img src="https://github.com/dnalegri/Entra-MFA/assets/164395911/bc79aecd-ec35-4b96-a2fd-f1d7290a92f3" />

*Ref 3: Add a name for the policy, and select the test group*
<img src="https://github.com/dnalegri/Entra-MFA/assets/164395911/f2417ff3-3f28-44eb-95a3-ef89a881aa80" />
*Ref 4: Select the resources the policy will apply to*
<img src="https://github.com/dnalegri/Entra-MFA/assets/164395911/bacec48f-54ca-44f0-9aba-a4c4a27fe497" />

*Ref 5: Select the access controls and apply the MFA option*
<img src="https://github.com/dnalegri/Entra-MFA/assets/164395911/562062ad-b1fb-4373-ba38-e2541f4fdf3f" />

*Ref 6: Enable the policy to ON*
<img src="https://github.com/dnalegri/Entra-MFA/assets/164395911/be9ecf70-3a02-432b-b8ea-e0fa0a3fc326" />

*Ref 7: Test the implementation with the test user account. Login to the resources with the active policy*
<img src="https://github.com/dnalegri/Entra-MFA/assets/164395911/6d13fc8f-ffbd-4613-a1e7-476d4d279549" />

*Ref 8: If the implementation is successful, the account will be prompted to set up an MFA method*
<img src="https://github.com/dnalegri/Entra-MFA/assets/164395911/29ed7c34-5162-416e-baa0-bd601e446aa4" />
<img src="https://github.com/dnalegri/Entra-MFA/assets/164395911/87853ba1-f811-40f4-a882-f7ecd0098dee" />
<img src="https://github.com/dnalegri/Entra-MFA/assets/164395911/0d63fabd-8c65-42d3-b170-8372ebc0da7d" />

*Ref 9: After the setup, log in to the resources. The test is successful if prompted for MFA*
<img src="https://github.com/dnalegri/Entra-MFA/assets/164395911/c02eceb6-8cbd-4b6e-98ab-007f79be0c43" />




