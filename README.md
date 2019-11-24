<h1 align="center">GitHub event trigger On cli</h1>


<p>
    <a href="https://github.com/hughcube/github-event-trigger/actions?query=workflow%3ADeploymentTriggerTest">
        <img src="https://github.com/hughcube/github-event-trigger/workflows/DeploymentTriggerTest/badge.svg" alt="DeploymentTriggerTest Actions status">
    </a>
    <a href="https://github.com/hughcube/github-event-trigger/actions?query=workflow%3ACompleteDeployment">
        <img src="https://github.com/hughcube/github-event-trigger/workflows/CompleteDeployment/badge.svg" alt="CompleteDeployment Actions status">
    </a>       
    <a href="https://github.com/hughcube/github-event-trigger">
        <img src="https://img.shields.io/badge/php-%3E%3D%207.0-8892BF.svg" alt="PHP Versions Supported">
    </a>
    <a href="https://packagist.org/packages/hughcube/github-event-trigger">
        <img src="https://poser.pugx.org/hughcube/github-event-trigger/version" alt="Latest Stable Version">
    </a>
    <a href="https://packagist.org/packages/hughcube/github-event-trigger">
        <img src="https://poser.pugx.org/hughcube/github-event-trigger/downloads" alt="Total Downloads">
    </a>
    <a href="https://github.com/hughcube/github-event-trigger/blob/master/LICENSE">
        <img src="https://img.shields.io/badge/license-MIT-428f7e.svg" alt="License">
    </a>
    <a href="https://packagist.org/packages/hughcube/github-event-trigger">
        <img src="https://poser.pugx.org/hughcube/github-event-trigger/v/unstable" alt="Latest Unstable Version">
    </a>
    <a href="https://packagist.org/packages/hughcube/github-event-trigger">
        <img src="https://poser.pugx.org/hughcube/github-event-trigger/composerlock" alt="composer.lock available">
    </a>
</p>

## Installing

```shell
$ composer require hughcube/github-event-trigger -vvv
```

## Trigger deploymentEvent on GitHub action

```shell
$ composer require hughcube/github-event-trigger:dev-master -vvv
$ ./vendor/bin/githubEventTrigger deployment --auth_http_token=${{ secrets.GITHUB_TOKEN }} --repository=${{ github.repository }}
```

## complete deployment on GitHub action

```shell
$ composer require hughcube/github-event-trigger:dev-master -vvv
$ ./vendor/bin/githubEventTrigger completeDeployment --auth_http_token=${{ secrets.GITHUB_TOKEN }} --repository=${{ github.repository }}
```
