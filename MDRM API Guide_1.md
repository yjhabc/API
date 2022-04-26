# MDRM REST API Guide

MDRM v4.6.2의 REST API 통합 가이드 문서입니다.



[TOC]

## 개요

이 문서는 워크플로우, 변경관리, 스케줄 작업에 대한 REST API에 대한 설명과 사용 방법을 제공합니다.

### 시작하기

###  아키텍처

## 준비 사항

## 인증

## API

### 워크플로우

### 스케줄

워크플로우, 점검작업 등 스케줄 작업과 관련된 API입니다.

#### Paths

##### PUT /schedule

> **Request**
>
> body (application/json;charset=UTF-8)
>
> Example code: edit-schedule
>
> ```json
> {
>   "sc_id": "1",
>   "sc_name": "test",
>   "sc_desc": "test desc",
>   "sc_type": "WORKFLOW_JOB",
>   "rep_type": "ONCE",
>   "start_date": "2022-01-26 11:16:33",
>   "rep_conf": {
>     "rep_year": "2022",
>     "rep_month": "01",
>     "rep_day": "26",
>     "rep_tm": "11:16:33"
>   },
>   "active_flg": "1",
>   "ref_ids": {
>     "grp_id": "G0000",
>     "job_id": [
>       31,
>       32
>     ]
>   },
>   "user_id": "mcuser"
> }
> ```
>
> **Response**
>
> | Code | Description | Links |
> | ---- | ----------- | ----- |
> | 200  | OK          | No    |
>
> 



### 변경관리



