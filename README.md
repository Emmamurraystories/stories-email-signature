# Stories Email Signature Generator

A single-page tool for Stories colleagues to generate their own branded email signature and copy it straight into Gmail.

## Usage

Open the hosted site, fill in your name, job title, and (optional) phone number, click **Copy signature**, then follow the on-page instructions to paste it into Gmail.

## Hosting

This is a static single-file site (`index.html`) with no build step. It is deployed on Netlify, connected to this GitHub repository. Any push to the default branch redeploys automatically.

## Editing

Everything lives in `index.html`: markup, styles, and the signature-building script. The Stories logo is embedded as a base64 data URI, so the file is fully self-contained.
