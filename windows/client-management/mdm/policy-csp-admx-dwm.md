---
title: Policy CSP - ADMX_DWM
description: Policy CSP - ADMX_DWM
ms.author: dansimp
ms.localizationpriority: medium
ms.topic: article
ms.prod: w10
ms.technology: windows
author: manikadhiman
ms.date: 08/31/2020
ms.reviewer: 
manager: dansimp
---

# Policy CSP - ADMX_DWM
> [!WARNING]
> Some information relates to prereleased products, which may be substantially modified before it's commercially released. Microsoft makes no warranties, expressed or implied, concerning the information provided here.

<hr/>

<!--Policies-->
## ADMX_DWM policies  

<dl>
  <dd>
    <a href="#admx-dwm-dwmdefaultcolorizationcolor-1">ADMX_DWM/DwmDefaultColorizationColor_1</a>
  </dd>
  <dd>
    <a href="#admx-dwm-dwmdefaultcolorizationcolor-2">ADMX_DWM/DwmDefaultColorizationColor_2</a>
  </dd>
  <dd>
    <a href="#admx-dwm-dwmdisableaccentandgradient">ADMX_DWM/DwmDisableAccentAndGradient</a>
  </dd>
  <dd>
    <a href="#admx-dwm-dwmdisallowanimations-1">ADMX_DWM/DwmDisallowAnimations_1</a>
  </dd>
  <dd>
    <a href="#admx-dwm-dwmdisallowanimations-2">ADMX_DWM/DwmDisallowAnimations_2</a>
  </dd>
  <dd>
    <a href="#admx-dwm-dwmdisallowcolorizationcolorchanges-1">ADMX_DWM/DwmDisallowColorizationColorChanges_1</a>
  </dd>
  <dd>
    <a href="#admx-dwm-dwmdisallowcolorizationcolorchanges-2">ADMX_DWM/DwmDisallowColorizationColorChanges_2</a>
  </dd>
  <dd>
    <a href="#admx-dwm-dwmdisallowflip3d-1">ADMX_DWM/DwmDisallowFlip3D_1</a>
  </dd>
  <dd>
    <a href="#admx-dwm-dwmdisallowflip3d-2">ADMX_DWM/DwmDisallowFlip3D_2</a>
  </dd>
</dl>


<hr/>

<!--Policy-->
<a href="" id="admx-dwm-dwmdefaultcolorizationcolor-1"></a>**ADMX_DWM/DwmDefaultColorizationColor_1**  

<!--SupportedSKUs-->
<table>
<tr>
    <th>Windows Edition</th>
    <th>Supported?</th>
</tr>
<tr>
    <td>Home</td>
    <td><img src="images/crossmark.png" alt="cross mark" /></td>
</tr>
<tr>
    <td>Pro</td>
    <td><img src="images/crossmark.png" alt="cross mark" /></td>
</tr>
<tr>
    <td>Business</td>
    <td><img src="images/crossmark.png" alt="cross mark" /></td>
</tr>
<tr>
    <td>Enterprise</td>
    <td><img src="images/checkmark.png" alt="check mark" /></td>
</tr>
<tr>
    <td>Education</td>
    <td><img src="images/crossmark.png" alt="cross mark" /></td>
</tr>
</table>

<!--/SupportedSKUs-->
<hr/>

<!--Scope-->
[Scope](./policy-configuration-service-provider.md#policy-scope):

> [!div class = "checklist"]
> * User

<hr/>

<!--/Scope-->
<!--Description-->
Available in Windows 10 Insider Preview Build 20185. This policy setting controls the default color for window frames when the user does not specify a color. 

If you enable this policy setting and specify a default color, this color is used in glass window frames, if the user does not specify a color. 

If you disable or do not configure this policy setting, the default internal color is used, if the user does not specify a color. 

> [!NOTE]
> This policy setting can be used in conjunction with the "Prevent color changes of window frames" setting, to enforce a specific color for window frames that cannot be changed by users.

<!--/Description-->
> [!TIP]
> This is an ADMX-backed policy and requires a special SyncML format to enable or disable.  For details, see [Understanding ADMX-backed policies](./understanding-admx-backed-policies.md).
> 
> You must specify the data type in the SyncML as &lt;Format&gt;chr&lt;/Format&gt;. For an example SyncML, refer to [Enabling a policy](./understanding-admx-backed-policies.md#enabling-a-policy).
> 
> The payload of the SyncML must be XML-encoded; for this XML encoding, there are a variety of online encoders that you can use. To avoid encoding the payload, you can use CDATA if your MDM supports it. For more information, see [CDATA Sections](http://www.w3.org/TR/REC-xml/#sec-cdata-sect).

<!--ADMXBacked-->
ADMX Info:  
-   GP English name: *Specify a default color*
-   GP name: *DefaultColorizationColorState*
-   GP path: *Windows Components/Desktop Window Manager/Window Frame Coloring*
-   GP ADMX file name: *DWM.admx*

<!--/ADMXBacked-->
<!--/Policy-->

<hr/>

<!--Policy-->
<a href="" id="admx-dwm-dwmdefaultcolorizationcolor-2"></a>**ADMX_DWM/DwmDefaultColorizationColor_2**  

<!--SupportedSKUs-->
<table>
<tr>
    <th>Windows Edition</th>
    <th>Supported?</th>
</tr>
<tr>
    <td>Home</td>
    <td><img src="images/crossmark.png" alt="cross mark" /></td>
</tr>
<tr>
    <td>Pro</td>
    <td><img src="images/crossmark.png" alt="cross mark" /></td>
</tr>
<tr>
    <td>Business</td>
    <td><img src="images/crossmark.png" alt="cross mark" /></td>
</tr>
<tr>
    <td>Enterprise</td>
    <td><img src="images/checkmark.png" alt="check mark" /></td>
</tr>
<tr>
    <td>Education</td>
    <td><img src="images/crossmark.png" alt="cross mark" /></td>
</tr>
</table>

<!--/SupportedSKUs-->
<hr/>

<!--Scope-->
[Scope](./policy-configuration-service-provider.md#policy-scope):

> [!div class = "checklist"]
> * Device

<hr/>

<!--/Scope-->
<!--Description-->
Available in Windows 10 Insider Preview Build 20185. This policy setting controls the default color for window frames when the user does not specify a color. 

If you enable this policy setting and specify a default color, this color is used in glass window frames, if the user does not specify a color. 

If you disable or do not configure this policy setting, the default internal color is used, if the user does not specify a color. 

> [!NOTE]
> This policy setting can be used in conjunction with the "Prevent color changes of window frames" setting, to enforce a specific color for window frames that cannot be changed by users.

<!--/Description-->
> [!TIP]
> This is an ADMX-backed policy and requires a special SyncML format to enable or disable.  For details, see [Understanding ADMX-backed policies](./understanding-admx-backed-policies.md).
> 
> You must specify the data type in the SyncML as &lt;Format&gt;chr&lt;/Format&gt;. For an example SyncML, refer to [Enabling a policy](./understanding-admx-backed-policies.md#enabling-a-policy).
> 
> The payload of the SyncML must be XML-encoded; for this XML encoding, there are a variety of online encoders that you can use. To avoid encoding the payload, you can use CDATA if your MDM supports it. For more information, see [CDATA Sections](http://www.w3.org/TR/REC-xml/#sec-cdata-sect).

<!--ADMXBacked-->
ADMX Info:  
-   GP English name: *Specify a default color*
-   GP name: *DefaultColorizationColorState*
-   GP path: *Windows Components/Desktop Window Manager/Window Frame Coloring*
-   GP ADMX file name: *DWM.admx*

<!--/ADMXBacked-->
<!--/Policy-->
<hr/>

<!--Policy-->
<a href="" id="admx-dwm-dwmdisableaccentandgradient"></a>**ADMX_DWM/DwmDisableAccentAndGradient**  

<!--SupportedSKUs-->
<table>
<tr>
    <th>Windows Edition</th>
    <th>Supported?</th>
</tr>
<tr>
    <td>Home</td>
    <td><img src="images/crossmark.png" alt="cross mark" /></td>
</tr>
<tr>
    <td>Pro</td>
    <td><img src="images/crossmark.png" alt="cross mark" /></td>
</tr>
<tr>
    <td>Business</td>
    <td><img src="images/crossmark.png" alt="cross mark" /></td>
</tr>
<tr>
    <td>Enterprise</td>
    <td><img src="images/checkmark.png" alt="check mark" /></td>
</tr>
<tr>
    <td>Education</td>
    <td><img src="images/crossmark.png" alt="cross mark" /></td>
</tr>
</table>

<!--/SupportedSKUs-->
<hr/>

<!--Scope-->
[Scope](./policy-configuration-service-provider.md#policy-scope):

> [!div class = "checklist"]
> * Device

<hr/>

<!--/Scope-->
<!--Description-->
Available in Windows 10 Insider Preview Build 20185. This policy setting controls the Start background visuals.

If you enable this policy setting, the Start background will use a solid color.

If you disable or do not configure this policy setting, the Start background will use the default visuals.

> [!NOTE]
> If this policy setting is enabled, users can continue to select a color in Start Personalization. However, setting the accent will have no effect.

<!--/Description-->
> [!TIP]
> This is an ADMX-backed policy and requires a special SyncML format to enable or disable.  For details, see [Understanding ADMX-backed policies](./understanding-admx-backed-policies.md).
> 
> You must specify the data type in the SyncML as &lt;Format&gt;chr&lt;/Format&gt;. For an example SyncML, refer to [Enabling a policy](./understanding-admx-backed-policies.md#enabling-a-policy).
> 
> The payload of the SyncML must be XML-encoded; for this XML encoding, there are a variety of online encoders that you can use. To avoid encoding the payload, you can use CDATA if your MDM supports it. For more information, see [CDATA Sections](http://www.w3.org/TR/REC-xml/#sec-cdata-sect).

<!--ADMXBacked-->
ADMX Info:  
-   GP English name: *Use solid color for Start background*
-   GP name: *DisableAccentGradient*
-   GP path: *Windows Components/Desktop Window Manager*
-   GP ADMX file name: *DWM.admx*

<!--/ADMXBacked-->
<!--/Policy-->
<hr/>

<!--Policy-->
<a href="" id="admx-dwm-dwmdisallowanimations-1"></a>**ADMX_DWM/DwmDisallowAnimations_1**  

<!--SupportedSKUs-->
<table>
<tr>
    <th>Windows Edition</th>
    <th>Supported?</th>
</tr>
<tr>
    <td>Home</td>
    <td><img src="images/crossmark.png" alt="cross mark" /></td>
</tr>
<tr>
    <td>Pro</td>
    <td><img src="images/crossmark.png" alt="cross mark" /></td>
</tr>
<tr>
    <td>Business</td>
    <td><img src="images/crossmark.png" alt="cross mark" /></td>
</tr>
<tr>
    <td>Enterprise</td>
    <td><img src="images/checkmark.png" alt="check mark" /></td>
</tr>
<tr>
    <td>Education</td>
    <td><img src="images/crossmark.png" alt="cross mark" /></td>
</tr>
</table>

<!--/SupportedSKUs-->
<hr/>

<!--Scope-->
[Scope](./policy-configuration-service-provider.md#policy-scope):

> [!div class = "checklist"]
> * User

<hr/>

<!--/Scope-->
<!--Description-->
Available in Windows 10 Insider Preview Build 20185. This policy setting controls the appearance of window animations such as those found when restoring, minimizing, and maximizing windows. 

If you enable this policy setting, window animations are turned off. 

If you disable or do not configure this policy setting, window animations are turned on. 

Changing this policy setting requires a logoff for it to be applied.

<!--/Description-->
> [!TIP]
> This is an ADMX-backed policy and requires a special SyncML format to enable or disable.  For details, see [Understanding ADMX-backed policies](./understanding-admx-backed-policies.md).
> 
> You must specify the data type in the SyncML as &lt;Format&gt;chr&lt;/Format&gt;. For an example SyncML, refer to [Enabling a policy](./understanding-admx-backed-policies.md#enabling-a-policy).
> 
> The payload of the SyncML must be XML-encoded; for this XML encoding, there are a variety of online encoders that you can use. To avoid encoding the payload, you can use CDATA if your MDM supports it. For more information, see [CDATA Sections](http://www.w3.org/TR/REC-xml/#sec-cdata-sect).

<!--ADMXBacked-->
ADMX Info:  
-   GP English name: *Do not allow window animations*
-   GP name: *DisallowAnimations*
-   GP path: *Windows Components/Desktop Window Manager*
-   GP ADMX file name: *DWM.admx*

<!--/ADMXBacked-->
<!--/Policy-->
<hr/>

<!--Policy-->
<a href="" id="admx-dwm-dwmdisallowanimations-2"></a>**ADMX_DWM/DwmDisallowAnimations_2**  

<!--SupportedSKUs-->
<table>
<tr>
    <th>Windows Edition</th>
    <th>Supported?</th>
</tr>
<tr>
    <td>Home</td>
    <td><img src="images/crossmark.png" alt="cross mark" /></td>
</tr>
<tr>
    <td>Pro</td>
    <td><img src="images/crossmark.png" alt="cross mark" /></td>
</tr>
<tr>
    <td>Business</td>
    <td><img src="images/crossmark.png" alt="cross mark" /></td>
</tr>
<tr>
    <td>Enterprise</td>
    <td><img src="images/checkmark.png" alt="check mark" /></td>
</tr>
<tr>
    <td>Education</td>
    <td><img src="images/crossmark.png" alt="cross mark" /></td>
</tr>
</table>

<!--/SupportedSKUs-->
<hr/>

<!--Scope-->
[Scope](./policy-configuration-service-provider.md#policy-scope):

> [!div class = "checklist"]
> * Device

<hr/>

<!--/Scope-->
<!--Description-->
Available in Windows 10 Insider Preview Build 20185. This policy setting controls the appearance of window animations such as those found when restoring, minimizing, and maximizing windows. 

If you enable this policy setting, window animations are turned off. 

If you disable or do not configure this policy setting, window animations are turned on. 

Changing this policy setting requires a logoff for it to be applied.

<!--/Description-->
> [!TIP]
> This is an ADMX-backed policy and requires a special SyncML format to enable or disable.  For details, see [Understanding ADMX-backed policies](./understanding-admx-backed-policies.md).
> 
> You must specify the data type in the SyncML as &lt;Format&gt;chr&lt;/Format&gt;. For an example SyncML, refer to [Enabling a policy](./understanding-admx-backed-policies.md#enabling-a-policy).
> 
> The payload of the SyncML must be XML-encoded; for this XML encoding, there are a variety of online encoders that you can use. To avoid encoding the payload, you can use CDATA if your MDM supports it. For more information, see [CDATA Sections](http://www.w3.org/TR/REC-xml/#sec-cdata-sect).

<!--ADMXBacked-->
ADMX Info:  
-   GP English name: *Do not allow window animations*
-   GP name: *DisallowAnimations*
-   GP path: *Windows Components/Desktop Window Manager*
-   GP ADMX file name: *DWM.admx*

<!--/ADMXBacked-->
<!--/Policy-->
<hr/>

<!--Policy-->
<a href="" id="admx-dwm-dwmdisallowcolorizationcolorchanges-1"></a>**ADMX_DWM/DwmDisallowColorizationColorChanges_1**  

<!--SupportedSKUs-->
<table>
<tr>
    <th>Windows Edition</th>
    <th>Supported?</th>
</tr>
<tr>
    <td>Home</td>
    <td><img src="images/crossmark.png" alt="cross mark" /></td>
</tr>
<tr>
    <td>Pro</td>
    <td><img src="images/crossmark.png" alt="cross mark" /></td>
</tr>
<tr>
    <td>Business</td>
    <td><img src="images/crossmark.png" alt="cross mark" /></td>
</tr>
<tr>
    <td>Enterprise</td>
    <td><img src="images/checkmark.png" alt="check mark" /></td>
</tr>
<tr>
    <td>Education</td>
    <td><img src="images/crossmark.png" alt="cross mark" /></td>
</tr>
</table>

<!--/SupportedSKUs-->
<hr/>

<!--Scope-->
[Scope](./policy-configuration-service-provider.md#policy-scope):

> [!div class = "checklist"]
> * User

<hr/>

<!--/Scope-->
<!--Description-->
Available in Windows 10 Insider Preview Build 20185. This policy setting controls the ability to change the color of window frames. 

If you enable this policy setting, you prevent users from changing the default window frame color. 

If you disable or do not configure this policy setting, you allow users to change the default window frame color. 

> [!NOTE]
> This policy setting can be used in conjunction with the "Specify a default color for window frames" policy setting, to enforce a specific color for window frames that cannot be changed by users.

<!--/Description-->
> [!TIP]
> This is an ADMX-backed policy and requires a special SyncML format to enable or disable.  For details, see [Understanding ADMX-backed policies](./understanding-admx-backed-policies.md).
> 
> You must specify the data type in the SyncML as &lt;Format&gt;chr&lt;/Format&gt;. For an example SyncML, refer to [Enabling a policy](./understanding-admx-backed-policies.md#enabling-a-policy).
> 
> The payload of the SyncML must be XML-encoded; for this XML encoding, there are a variety of online encoders that you can use. To avoid encoding the payload, you can use CDATA if your MDM supports it. For more information, see [CDATA Sections](http://www.w3.org/TR/REC-xml/#sec-cdata-sect).

<!--ADMXBacked-->
ADMX Info:  
-   GP English name: *Do not allow color changes*
-   GP name: *DisallowColorizationColorChanges*
-   GP path: *Windows Components/Desktop Window Manager/Window Frame Coloring*
-   GP ADMX file name: *DWM.admx*

<!--/ADMXBacked-->
<!--/Policy-->
<hr/>

<!--Policy-->
<a href="" id="admx-dwm-dwmdisallowcolorizationcolorchanges-2"></a>**ADMX_DWM/DwmDisallowColorizationColorChanges_2**  

<!--SupportedSKUs-->
<table>
<tr>
    <th>Windows Edition</th>
    <th>Supported?</th>
</tr>
<tr>
    <td>Home</td>
    <td><img src="images/crossmark.png" alt="cross mark" /></td>
</tr>
<tr>
    <td>Pro</td>
    <td><img src="images/crossmark.png" alt="cross mark" /></td>
</tr>
<tr>
    <td>Business</td>
    <td><img src="images/crossmark.png" alt="cross mark" /></td>
</tr>
<tr>
    <td>Enterprise</td>
    <td><img src="images/checkmark.png" alt="check mark" /></td>
</tr>
<tr>
    <td>Education</td>
    <td><img src="images/crossmark.png" alt="cross mark" /></td>
</tr>
</table>

<!--/SupportedSKUs-->
<hr/>

<!--Scope-->
[Scope](./policy-configuration-service-provider.md#policy-scope):

> [!div class = "checklist"]
> * Device

<hr/>

<!--/Scope-->
<!--Description-->
Available in Windows 10 Insider Preview Build 20185. This policy setting controls the ability to change the color of window frames. 

If you enable this policy setting, you prevent users from changing the default window frame color. 

If you disable or do not configure this policy setting, you allow users to change the default window frame color. 

> [!NOTE] 
> This policy setting can be used in conjunction with the "Specify a default color for window frames" policy setting, to enforce a specific color for window frames that cannot be changed by users.

<!--/Description-->
> [!TIP]
> This is an ADMX-backed policy and requires a special SyncML format to enable or disable.  For details, see [Understanding ADMX-backed policies](./understanding-admx-backed-policies.md).
> 
> You must specify the data type in the SyncML as &lt;Format&gt;chr&lt;/Format&gt;. For an example SyncML, refer to [Enabling a policy](./understanding-admx-backed-policies.md#enabling-a-policy).
> 
> The payload of the SyncML must be XML-encoded; for this XML encoding, there are a variety of online encoders that you can use. To avoid encoding the payload, you can use CDATA if your MDM supports it. For more information, see [CDATA Sections](http://www.w3.org/TR/REC-xml/#sec-cdata-sect).

<!--ADMXBacked-->
ADMX Info:  
-   GP English name: *Do not allow color changes*
-   GP name: *DisallowColorizationColorChanges*
-   GP path: *Windows Components/Desktop Window Manager/Window Frame Coloring*
-   GP ADMX file name: *DWM.admx*

<!--/ADMXBacked-->
<!--/Policy-->
<hr/>

<!--Policy-->
<a href="" id="admx-dwm-dwmdisallowflip3d-1"></a>**ADMX_DWM/DwmDisallowFlip3D_1**  

<!--SupportedSKUs-->
<table>
<tr>
    <th>Windows Edition</th>
    <th>Supported?</th>
</tr>
<tr>
    <td>Home</td>
    <td><img src="images/crossmark.png" alt="cross mark" /></td>
</tr>
<tr>
    <td>Pro</td>
    <td><img src="images/crossmark.png" alt="cross mark" /></td>
</tr>
<tr>
    <td>Business</td>
    <td><img src="images/crossmark.png" alt="cross mark" /></td>
</tr>
<tr>
    <td>Enterprise</td>
    <td><img src="images/checkmark.png" alt="check mark" /></td>
</tr>
<tr>
    <td>Education</td>
    <td><img src="images/crossmark.png" alt="cross mark" /></td>
</tr>
</table>

<!--/SupportedSKUs-->
<hr/>

<!--Scope-->
[Scope](./policy-configuration-service-provider.md#policy-scope):

> [!div class = "checklist"]
> * User

<hr/>

<!--/Scope-->
<!--Description-->
Available in Windows 10 Insider Preview Build 20185. This policy setting allows you to configure the accessibility of the Flip 3D feature. Flip 3D allows the user to view items on the Windows desktop as they are being flipped through in three dimensions. 

If you enable this policy setting, Flip 3D is inaccessible. 

If you disable or do not configure this policy setting, Flip 3D is accessible, if desktop composition is turned on. When Windows Flip 3D is activated with the Windows+Tab keys, a visual version of the desktop is presented and items can be flipped through to select. 

Changing this policy setting requires a logoff for it to be applied.

<!--/Description-->
> [!TIP]
> This is an ADMX-backed policy and requires a special SyncML format to enable or disable.  For details, see [Understanding ADMX-backed policies](./understanding-admx-backed-policies.md).
> 
> You must specify the data type in the SyncML as &lt;Format&gt;chr&lt;/Format&gt;. For an example SyncML, refer to [Enabling a policy](./understanding-admx-backed-policies.md#enabling-a-policy).
> 
> The payload of the SyncML must be XML-encoded; for this XML encoding, there are a variety of online encoders that you can use. To avoid encoding the payload, you can use CDATA if your MDM supports it. For more information, see [CDATA Sections](http://www.w3.org/TR/REC-xml/#sec-cdata-sect).

<!--ADMXBacked-->
ADMX Info:  
-   GP English name: *Do not allow Flip3D invocation*
-   GP name: *DisallowFlip3d*
-   GP path: *Windows Components/Desktop Window Manager*
-   GP ADMX file name: *DWM.admx*

<!--/ADMXBacked-->
<!--/Policy-->
<hr/>

<!--Policy-->
<a href="" id="admx-dwm-dwmdisallowflip3d-2"></a>**ADMX_DWM/DwmDisallowFlip3D_2**  

<!--SupportedSKUs-->
<table>
<tr>
    <th>Windows Edition</th>
    <th>Supported?</th>
</tr>
<tr>
    <td>Home</td>
    <td><img src="images/crossmark.png" alt="cross mark" /></td>
</tr>
<tr>
    <td>Pro</td>
    <td><img src="images/crossmark.png" alt="cross mark" /></td>
</tr>
<tr>
    <td>Business</td>
    <td><img src="images/crossmark.png" alt="cross mark" /></td>
</tr>
<tr>
    <td>Enterprise</td>
    <td><img src="images/checkmark.png" alt="check mark" /></td>
</tr>
<tr>
    <td>Education</td>
    <td><img src="images/crossmark.png" alt="cross mark" /></td>
</tr>
</table>

<!--/SupportedSKUs-->
<hr/>

<!--Scope-->
[Scope](./policy-configuration-service-provider.md#policy-scope):

> [!div class = "checklist"]
> * Device

<hr/>

<!--/Scope-->
<!--Description-->
Available in Windows 10 Insider Preview Build 20185. This policy setting allows you to configure the accessibility of the Flip 3D feature. Flip 3D allows the user to view items on the Windows desktop as they are being flipped through in three dimensions. 

If you enable this policy setting, Flip 3D is inaccessible. 

If you disable or do not configure this policy setting, Flip 3D is accessible, if desktop composition is turned on. When Windows Flip 3D is activated with the Windows+Tab keys, a visual version of the desktop is presented and items can be flipped through to select. 

Changing this policy setting requires a logoff for it to be applied.

<!--/Description-->
> [!TIP]
> This is an ADMX-backed policy and requires a special SyncML format to enable or disable.  For details, see [Understanding ADMX-backed policies](./understanding-admx-backed-policies.md).
> 
> You must specify the data type in the SyncML as &lt;Format&gt;chr&lt;/Format&gt;. For an example SyncML, refer to [Enabling a policy](./understanding-admx-backed-policies.md#enabling-a-policy).
> 
> The payload of the SyncML must be XML-encoded; for this XML encoding, there are a variety of online encoders that you can use. To avoid encoding the payload, you can use CDATA if your MDM supports it. For more information, see [CDATA Sections](http://www.w3.org/TR/REC-xml/#sec-cdata-sect).

<!--ADMXBacked-->
ADMX Info:  
-   GP English name: *Do not allow Flip3D invocation*
-   GP name: *DisallowFlip3d*
-   GP path: *Windows Components/Desktop Window Manager*
-   GP ADMX file name: *DWM.admx*

<!--/ADMXBacked-->
<!--/Policy-->
<hr/>

Footnotes:

- 1 - Available in Windows 10, version 1607.
- 2 - Available in Windows 10, version 1703.
- 3 - Available in Windows 10, version 1709.
- 4 - Available in Windows 10, version 1803.
- 5 - Available in Windows 10, version 1809.
- 6 - Available in Windows 10, version 1903.
- 7 - Available in Windows 10, version 1909.
- 8 - Available in Windows 10, version 2004.

<!--/Policies-->

