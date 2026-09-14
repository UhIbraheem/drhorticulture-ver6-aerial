# drhorticulture-ver6-aerial

Estimating plant nutrition from top-down RGB images.

FIU CIS4951 Capstone 2, Fall 2026. Team B.

## What this is

Growers over-fertilize because they have no cheap way to tell which plants
actually need nitrogen. The extra runs off into the water and feeds algae which
creates algae blooms.

Lab instruments measure this well but one plant at a time, and they rely on
near-infrared light that normal cameras block. We are testing how far you can
get with just red, green and blue, on a top-down image covering many plants,
and measuring how much accuracy that costs against the lab's readings.

Team A on the same project handles close-up single-plant photos and the
fertilizer recommendation. We handle the top-down view.

## Status

Project setup phase

## Layout

    data/        images and reference readings 
    src/         pipeline code
    frontend/    user interface
    notebooks/   exploration
    tests/
    results/     metrics and figures
    docs/        design doc, spec, plan

## Setup

    python -m venv .venv
    source .venv/bin/activate
    pip install -r requirements.txt

Windows: `.venv\Scripts\activate`

## Data

Images belong to Dr. Khoddamzadeh's lab and are not in this repo.

## Team

Moises Perez Fernandez (lead), Ibraheem Mohammad, Ulises Cheong Borges,
Jorge Luis Ponce Diaz, Santiago Morales Villarreal

Product Owner: Dr. Amir Khoddamzadeh, FIU Earth and Environment
Course: CIS4951, Prof. Masoud Sadjadi
