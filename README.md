# CookieBeam Consent Mode v2 Template for Google Tag Manager

This repository contains the official Google Tag Manager (GTM) template for CookieBeam.

With this template, you can easily integrate CookieBeam's Consent Management Platform with Google Tag Manager. It handles Google Consent Mode v2 signaling (Basic & Advanced) and manages the loading of the CookieBeam banner.

## Features

-   **Google Consent Mode v2 Support:** Automatically handles `ad_storage`, `analytics_storage`, `ad_user_data`, and `ad_personalization` signals.
-   **Microsoft Consent Mode Support:** Supports Microsoft UET and Clarity consent signaling.
-   **Zero-Dependency Loading:** Loads the banner script via a high-performance CDN.
-   **Regional Defaults:** Configure specific consent defaults for different regions (e.g., EEA vs. US).

## Implementation Guide

1.  Create a **CookieBeam** account if you haven't already.
2.  Get your **Banner ID** from the CookieBeam dashboard.
3.  In Google Tag Manager, search for "CookieBeam" in the Community Template Gallery (once published) or import this template manually.
4.  Create a new tag using this template.
5.  Set the trigger to **Consent Initialization - All Pages**.

## Repository Structure

-   `template.tpl`: The GTM template definition.
-   `metadata.yaml`: Version history and metadata for the GTM Gallery.
-   `LICENSE`: Apache 2.0 License.

## License

Licensed under the Apache License, Version 2.0.