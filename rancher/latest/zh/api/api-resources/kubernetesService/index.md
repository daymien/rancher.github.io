---
title: API
layout: rancher-default
version: latest
lang: zh
---

## kubernetesService



### Resource Fields

Field | Type | Create | Update | Default | Notes
---|---|---|---|---|---
description | string | Optional | Yes | - | 
environmentId | [environment]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/api-resources/environment/) | Yes | - | - | 
externalId | string | - | - | - | 
healthState | string | - | - | - | 
id | int | - | - | - | The unique identifier for the kubernetesService
name | string | Yes | Yes | - | 
selectorContainer | string | - | - | - | 
template | json | - | - | - | 
vip | string | - | - | - | 


Please read more about the [common resource fields]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/common/). 
These fields are read only and applicable to almost every resource. We have segregated them from the list above.








### Actions

<div class="action">
<span class="header">
activate
<span class="headerright">POST:  <code>${actions.activate}</code></span></span>
<div class="action-contents">
To activate the kubernetesService
<br>

<span class="input">
<strong>Input:</strong>This action has no inputs</span>
<br>

<br>


<span class="output"><strong>Output:</strong> An updated copy of the <a href="/rancher/api/api-resources/service/">service</a> resource</span>
</div>
</div>

<div class="action">
<span class="header">
addservicelink
<span class="headerright">POST:  <code>${actions.addservicelink}</code></span></span>
<div class="action-contents">
To addservicelink the kubernetesService
<br>

<span class="input">
<strong>Input:</strong> addRemoveServiceLinkInput
</span>

Field | Type | Required | Default | Notes
---|---|---|---|---
serviceLink | serviceLink | Yes |  | 


<br>
{% highlight json %}{

	"serviceLink": {

		"name": "string",

		"serviceId": "reference[service]",

		"uuid": "string"

	}

}{% endhighlight %}

<br>


<span class="output"><strong>Output:</strong> An updated copy of the <a href="/rancher/api/api-resources/service/">service</a> resource</span>
</div>
</div>

<div class="action">
<span class="header">
cancelrollback
<span class="headerright">POST:  <code>${actions.cancelrollback}</code></span></span>
<div class="action-contents">
To cancelrollback the kubernetesService
<br>

<span class="input">
<strong>Input:</strong>This action has no inputs</span>
<br>

<br>


<span class="output"><strong>Output:</strong> An updated copy of the <a href="/rancher/api/api-resources/service/">service</a> resource</span>
</div>
</div>

<div class="action">
<span class="header">
cancelupgrade
<span class="headerright">POST:  <code>${actions.cancelupgrade}</code></span></span>
<div class="action-contents">
To cancelupgrade the kubernetesService
<br>

<span class="input">
<strong>Input:</strong>This action has no inputs</span>
<br>

<br>


<span class="output"><strong>Output:</strong> An updated copy of the <a href="/rancher/api/api-resources/service/">service</a> resource</span>
</div>
</div>

<div class="action">
<span class="header">
deactivate
<span class="headerright">POST:  <code>${actions.deactivate}</code></span></span>
<div class="action-contents">
To deactivate the kubernetesService
<br>

<span class="input">
<strong>Input:</strong>This action has no inputs</span>
<br>

<br>


<span class="output"><strong>Output:</strong> An updated copy of the <a href="/rancher/api/api-resources/service/">service</a> resource</span>
</div>
</div>

<div class="action">
<span class="header">
finishupgrade
<span class="headerright">POST:  <code>${actions.finishupgrade}</code></span></span>
<div class="action-contents">
To finishupgrade the kubernetesService
<br>

<span class="input">
<strong>Input:</strong>This action has no inputs</span>
<br>

<br>


<span class="output"><strong>Output:</strong> An updated copy of the <a href="/rancher/api/api-resources/service/">service</a> resource</span>
</div>
</div>

<div class="action">
<span class="header">
remove
<span class="headerright">POST:  <code>${actions.remove}</code></span></span>
<div class="action-contents">
To remove the kubernetesService
<br>

<span class="input">
<strong>Input:</strong>This action has no inputs</span>
<br>

<br>


<span class="output"><strong>Output:</strong> An updated copy of the <a href="/rancher/api/api-resources/service/">service</a> resource</span>
</div>
</div>

<div class="action">
<span class="header">
removeservicelink
<span class="headerright">POST:  <code>${actions.removeservicelink}</code></span></span>
<div class="action-contents">
To removeservicelink the kubernetesService
<br>

<span class="input">
<strong>Input:</strong> addRemoveServiceLinkInput
</span>

Field | Type | Required | Default | Notes
---|---|---|---|---
serviceLink | serviceLink | Yes |  | 


<br>
{% highlight json %}{

	"serviceLink": {

		"name": "string",

		"serviceId": "reference[service]",

		"uuid": "string"

	}

}{% endhighlight %}

<br>


<span class="output"><strong>Output:</strong> An updated copy of the <a href="/rancher/api/api-resources/service/">service</a> resource</span>
</div>
</div>

<div class="action">
<span class="header">
restart
<span class="headerright">POST:  <code>${actions.restart}</code></span></span>
<div class="action-contents">
To restart the kubernetesService
<br>

<span class="input">
<strong>Input:</strong> serviceRestart
</span>

Field | Type | Required | Default | Notes
---|---|---|---|---
rollingRestartStrategy | rollingRestartStrategy | Yes |  | 


<br>
{% highlight json %}{

	"rollingRestartStrategy": {

		"batchSize": 1,

		"intervalMillis": 2000

	}

}{% endhighlight %}

<br>


<span class="output"><strong>Output:</strong> An updated copy of the <a href="/rancher/api/api-resources/service/">service</a> resource</span>
</div>
</div>

<div class="action">
<span class="header">
rollback
<span class="headerright">POST:  <code>${actions.rollback}</code></span></span>
<div class="action-contents">
To rollback the kubernetesService
<br>

<span class="input">
<strong>Input:</strong>This action has no inputs</span>
<br>

<br>


<span class="output"><strong>Output:</strong> An updated copy of the <a href="/rancher/api/api-resources/service/">service</a> resource</span>
</div>
</div>

<div class="action">
<span class="header">
setservicelinks
<span class="headerright">POST:  <code>${actions.setservicelinks}</code></span></span>
<div class="action-contents">
To setservicelinks the kubernetesService
<br>

<span class="input">
<strong>Input:</strong> setServiceLinksInput
</span>

Field | Type | Required | Default | Notes
---|---|---|---|---
serviceLinks | array[serviceLink] | No |  | The list of services linked


<br>
{% highlight json %}{

	"serviceLinks": "array[serviceLink]"

}{% endhighlight %}

<br>


<span class="output"><strong>Output:</strong> An updated copy of the <a href="/rancher/api/api-resources/service/">service</a> resource</span>
</div>
</div>

<div class="action">
<span class="header">
upgrade
<span class="headerright">POST:  <code>${actions.upgrade}</code></span></span>
<div class="action-contents">
To upgrade the kubernetesService
<br>

<span class="input">
<strong>Input:</strong> serviceUpgrade
</span>

Field | Type | Required | Default | Notes
---|---|---|---|---
inServiceStrategy | inServiceUpgradeStrategy | No |  | 
toServiceStrategy | toServiceUpgradeStrategy | No |  | 


<br>
{% highlight json %}{

	"inServiceStrategy": {

		"batchSize": 1,

		"intervalMillis": 2000,

		"launchConfig": {

			"accountId": "reference[account]",

			"build": {

				"context": "string",

				"dockerfile": "string",

				"forcerm": true,

				"nocache": true,

				"remote": "string",

				"rm": true

			},

			"capAdd": "array[enum]",

			"capDrop": "array[enum]",

			"command": [

				"string1",

				"string2",

				"...stringN"

			],

			"count": 0,

			"cpuSet": "string",

			"cpuShares": 0,

			"createIndex": 0,

			"created": "date",

			"dataVolumeMounts": "map[reference[volume]]",

			"dataVolumes": [

				"string1",

				"string2",

				"...stringN"

			],

			"dataVolumesFrom": "array[reference[container]]",

			"dataVolumesFromLaunchConfigs": [

				"string1",

				"string2",

				"...stringN"

			],

			"deploymentUnitUuid": "string",

			"description": "string",

			"devices": [

				"string1",

				"string2",

				"...stringN"

			],

			"disks": "array[virtualMachineDisk]",

			"dns": [

				"string1",

				"string2",

				"...stringN"

			],

			"dnsSearch": [

				"string1",

				"string2",

				"...stringN"

			],

			"domainName": "string",

			"entryPoint": [

				"string1",

				"string2",

				"...stringN"

			],

			"environment": {

				"key1": "value1",

				"key2": "value2",

				"keyN": "valueN"

			},

			"expose": [

				"string1",

				"string2",

				"...stringN"

			],

			"externalId": "string",

			"extraHosts": [

				"string1",

				"string2",

				"...stringN"

			],

			"firstRunning": "date",

			"healthCheck": {

				"healthyThreshold": 0,

				"initializingTimeout": 0,

				"interval": 0,

				"name": "string",

				"port": 0,

				"recreateOnQuorumStrategyConfig": {

					"quorum": 0

				},

				"reinitializingTimeout": 0,

				"requestLine": "string",

				"responseTimeout": 0,

				"strategy": "recreate",

				"unhealthyThreshold": 0

			},

			"healthState": "enum",

			"hostId": "reference[host]",

			"hostname": "string",

			"id": 0,

			"imageUuid": "string",

			"instanceLinks": "map[reference[instance]]",

			"kind": "container",

			"labels": {

				"key1": "value1",

				"key2": "value2",

				"keyN": "valueN"

			},

			"logConfig": {

				"config": {

					"key1": "value1",

					"key2": "value2",

					"keyN": "valueN"

				},

				"driver": "string"

			},

			"lxcConf": {

				"key1": "value1",

				"key2": "value2",

				"keyN": "valueN"

			},

			"memory": 0,

			"memoryMb": 0,

			"memorySwap": 0,

			"nativeContainer": true,

			"networkContainerId": "reference[container]",

			"networkIds": "array[reference[network]]",

			"networkLaunchConfig": "string",

			"networkMode": "managed",

			"pidMode": "enum",

			"ports": [

				"string1",

				"string2",

				"...stringN"

			],

			"primaryIpAddress": "string",

			"privileged": false,

			"publishAllPorts": false,

			"readOnly": false,

			"registryCredentialId": "reference[registryCredential]",

			"removed": "date",

			"requestedHostId": "reference[host]",

			"requestedIpAddress": "string",

			"securityOpt": [

				"string1",

				"string2",

				"...stringN"

			],

			"startCount": 0,

			"startOnCreate": true,

			"state": "enum",

			"stdinOpen": false,

			"systemContainer": "enum",

			"transitioning": "enum",

			"transitioningMessage": "string",

			"transitioningProgress": 0,

			"tty": false,

			"user": "string",

			"userdata": "string",

			"uuid": "string",

			"vcpu": 1,

			"version": "0",

			"volumeDriver": "string",

			"workingDir": "string"

		},

		"previousLaunchConfig": {

			"accountId": "reference[account]",

			"build": {

				"context": "string",

				"dockerfile": "string",

				"forcerm": true,

				"nocache": true,

				"remote": "string",

				"rm": true

			},

			"capAdd": "array[enum]",

			"capDrop": "array[enum]",

			"command": [

				"string1",

				"string2",

				"...stringN"

			],

			"count": 0,

			"cpuSet": "string",

			"cpuShares": 0,

			"createIndex": 0,

			"created": "date",

			"dataVolumeMounts": "map[reference[volume]]",

			"dataVolumes": [

				"string1",

				"string2",

				"...stringN"

			],

			"dataVolumesFrom": "array[reference[container]]",

			"dataVolumesFromLaunchConfigs": [

				"string1",

				"string2",

				"...stringN"

			],

			"deploymentUnitUuid": "string",

			"description": "string",

			"devices": [

				"string1",

				"string2",

				"...stringN"

			],

			"disks": "array[virtualMachineDisk]",

			"dns": [

				"string1",

				"string2",

				"...stringN"

			],

			"dnsSearch": [

				"string1",

				"string2",

				"...stringN"

			],

			"domainName": "string",

			"entryPoint": [

				"string1",

				"string2",

				"...stringN"

			],

			"environment": {

				"key1": "value1",

				"key2": "value2",

				"keyN": "valueN"

			},

			"expose": [

				"string1",

				"string2",

				"...stringN"

			],

			"externalId": "string",

			"extraHosts": [

				"string1",

				"string2",

				"...stringN"

			],

			"firstRunning": "date",

			"healthCheck": {

				"healthyThreshold": 0,

				"initializingTimeout": 0,

				"interval": 0,

				"name": "string",

				"port": 0,

				"recreateOnQuorumStrategyConfig": {

					"quorum": 0

				},

				"reinitializingTimeout": 0,

				"requestLine": "string",

				"responseTimeout": 0,

				"strategy": "recreate",

				"unhealthyThreshold": 0

			},

			"healthState": "enum",

			"hostId": "reference[host]",

			"hostname": "string",

			"id": 0,

			"imageUuid": "string",

			"instanceLinks": "map[reference[instance]]",

			"kind": "container",

			"labels": {

				"key1": "value1",

				"key2": "value2",

				"keyN": "valueN"

			},

			"logConfig": {

				"config": {

					"key1": "value1",

					"key2": "value2",

					"keyN": "valueN"

				},

				"driver": "string"

			},

			"lxcConf": {

				"key1": "value1",

				"key2": "value2",

				"keyN": "valueN"

			},

			"memory": 0,

			"memoryMb": 0,

			"memorySwap": 0,

			"nativeContainer": true,

			"networkContainerId": "reference[container]",

			"networkIds": "array[reference[network]]",

			"networkLaunchConfig": "string",

			"networkMode": "managed",

			"pidMode": "enum",

			"ports": [

				"string1",

				"string2",

				"...stringN"

			],

			"primaryIpAddress": "string",

			"privileged": false,

			"publishAllPorts": false,

			"readOnly": false,

			"registryCredentialId": "reference[registryCredential]",

			"removed": "date",

			"requestedHostId": "reference[host]",

			"requestedIpAddress": "string",

			"securityOpt": [

				"string1",

				"string2",

				"...stringN"

			],

			"startCount": 0,

			"startOnCreate": true,

			"state": "enum",

			"stdinOpen": false,

			"systemContainer": "enum",

			"transitioning": "enum",

			"transitioningMessage": "string",

			"transitioningProgress": 0,

			"tty": false,

			"user": "string",

			"userdata": "string",

			"uuid": "string",

			"vcpu": 1,

			"version": "0",

			"volumeDriver": "string",

			"workingDir": "string"

		},

		"previousSecondaryLaunchConfigs": "array[secondaryLaunchConfig]",

		"secondaryLaunchConfigs": "array[secondaryLaunchConfig]",

		"startFirst": false

	},

	"toServiceStrategy": {

		"batchSize": 1,

		"finalScale": 1,

		"intervalMillis": 2000,

		"toServiceId": "reference[service]",

		"updateLinks": true

	}

}{% endhighlight %}

<br>


<span class="output"><strong>Output:</strong> An updated copy of the <a href="/rancher/api/api-resources/service/">service</a> resource</span>
</div>
</div>

