---
layout: default
title: "Bab 11: Integrasi dengan Praktik ITSM"
parent: "Bagian III: Implementasi Teknis"
nav_order: 11
permalink: /id/chapters/11-itsm-integration/
lang: id
---

# Bab 11: Integrasi dengan Praktik ITSM

## Tujuan Pembelajaran

- Mengintegrasikan manajemen tenaga kerja dengan praktik ITSM
- Menyelaraskan kompetensi dengan kebutuhan layanan
- Mengoptimalkan alokasi sumber daya untuk penyampaian layanan

---

## Poin Integrasi Utama

### Matriks Integrasi

| Praktik ITSM | Area Integrasi | Manfaat |
|--------------|----------------|---------|
| **Incident Management** | Staffing, skill routing | Resolusi lebih cepat |
| **Problem Management** | Expert assignment | RCA lebih baik |
| **Change Management** | Resource planning | Implementasi sukses |
| **Service Level Management** | Capacity planning | SLA achievement |
| **Knowledge Management** | Training, dokumentasi | Knowledge retention |

---

## Integrasi dengan Service Desk

### Workforce Planning untuk Service Desk

```
┌─────────────────────────────────────────────────────────────────┐
│                 SERVICE DESK WORKFORCE PLANNING                  │
├─────────────────────────────────────────────────────────────────┤
│                                                                 │
│   Volume Demand → Capacity Planning → Scheduling → Performance  │
│                                                                 │
│   ┌──────────────┐  ┌──────────────┐  ┌──────────────┐         │
│   │ Historical   │  │  FTE         │  │  Shift       │         │
│   │ Ticket Data  │─►│  Calculation │─►│  Scheduling  │         │
│   └──────────────┘  └──────────────┘  └──────────────┘         │
│                                                                 │
└─────────────────────────────────────────────────────────────────┘
```

---

## Skill-Based Routing

### Matriks Keterampilan untuk Routing

| Kategori Tiket | Keterampilan Required | Tim |
|----------------|----------------------|-----|
| Network Issues | CCNA, Network+ | Network Team |
| Application Bugs | Java, .NET | Dev Support |
| Security Incidents | CISSP, Security+ | Security Team |
| Database Issues | DBA, SQL | Database Team |

---

## Capacity Management Integration

### Menghubungkan Kapasitas dengan SLA

| Service | SLA Target | Required Capacity | Current | Gap |
|---------|------------|-------------------|---------|-----|
| P1 Incident | 1 hour | 5 FTE 24/7 | 4 FTE | -1 |
| P2 Incident | 4 hours | 10 FTE | 10 FTE | 0 |
| Service Request | 24 hours | 8 FTE | 7 FTE | -1 |

---

## Ringkasan

Integrasi yang efektif memastikan:
- Sumber daya yang tepat untuk penyampaian layanan
- Routing berbasis keterampilan yang optimal
- Kapasitas yang memadai untuk memenuhi SLA
- Knowledge transfer yang berkelanjutan

---

[Bab Sebelumnya](/TalentAndWorkforceManagementHandbook/id/chapters/10-performance-management/) | [Bab Selanjutnya](/TalentAndWorkforceManagementHandbook/id/chapters/12-kpis-metrics/) | [Daftar Isi](/TalentAndWorkforceManagementHandbook/id/table-of-contents/)
