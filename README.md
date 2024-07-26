# Enclude-Consents-Email-Opt-Out

An optional add-on to the [Enclude Consents](https://github.com/EncludeLtd/Consents) package. Ensure the Enclude Consents package is installed before attempting to install this add-on.

## Deploy

<a href="https://github.com/Enclude-Components/Enclude-Consents-Email-Opt-Out/releases/latest">
  <img alt="Install Latest Release"
       src="https://img.shields.io/badge/Install%20Latest%20Release-238636?style=for-the-badge&logoColor=white&logo=DocuSign">
</a>

## Description
Adds a rollup field to Consent Profile called `Email Opt Out`. This field counts the number of Consent Assignment records where the "Email" Consent Type has been "Denied". The "Email" Consent Type record has not been included in this add-on, and must be created manually. If you wish to name your Consent Type record something other than "Email," the rollup field must be modified.

It also includes a flow `Consent Profile On Insert Update Email Opt Out` which syncs the standard Contact `Email Opt Out` field with the one on Consent Profile.

This add-on can also be used as a general example for how to create Consent Profile rollups and record-triggered flows for those fields.

## Contents

- Flows
    - Consent Profile On Insert Update Email Opt Out
- Custom Fields
    - Consent Profile
        - Email Opt Out