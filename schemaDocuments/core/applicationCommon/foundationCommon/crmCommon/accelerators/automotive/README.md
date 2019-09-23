
# automotive


## Entities

|Name|Description|
|---|---|
|[AggregateKPI](https://docs.microsoft.com/en-us/common-data-model/schema/core/applicationcommon/foundationcommon/crmcommon/accelerators/automotive/AggregateKPI)|Type of KPIs that can be useful for tracking customer, device or business performance.  |
|[AggregateKPIContext](https://docs.microsoft.com/en-us/common-data-model/schema/core/applicationcommon/foundationcommon/crmcommon/accelerators/automotive/AggregateKPIContext)|Context of a given customer, device, business operation or user, in which a given aggregate KPI may be applicable and may have a given target value.  |
|[AggregateKPIMeasurement](https://docs.microsoft.com/en-us/common-data-model/schema/core/applicationcommon/foundationcommon/crmcommon/accelerators/automotive/AggregateKPIMeasurement)|Measured value for a given aggregate KPI in a given context.  |
|[AttributeGroup](https://docs.microsoft.com/en-us/common-data-model/schema/core/applicationcommon/foundationcommon/crmcommon/accelerators/automotive/AttributeGroup)|Group of attribute types, for example representing dimensions, interior, exterior, environmental or other aspects of a device.  |
|[AttributeOption](https://docs.microsoft.com/en-us/common-data-model/schema/core/applicationcommon/foundationcommon/crmcommon/accelerators/automotive/AttributeOption)|Available option for an attribute type that require its value to be selected from a list.  |
|[AttributeType](https://docs.microsoft.com/en-us/common-data-model/schema/core/applicationcommon/foundationcommon/crmcommon/accelerators/automotive/AttributeType)|Type of entry in a device specification, such as length, fuel type, color or any other property that characterizes a given device.  |
|[AutoLeadToOpportunitySalesProcess](https://docs.microsoft.com/en-us/common-data-model/schema/core/applicationcommon/foundationcommon/crmcommon/accelerators/automotive/AutoLeadToOpportunitySalesProcess)|Base entity for process Auto Lead to Opportunity Sales Process  |
|[Business](https://docs.microsoft.com/en-us/common-data-model/schema/core/applicationcommon/foundationcommon/crmcommon/accelerators/automotive/Business)|Legal entity or organization representing, for example, a national sales company, importer, distributor, dealer group or dealer in the ecosystem.  |
|[BusinessFacility](https://docs.microsoft.com/en-us/common-data-model/schema/core/applicationcommon/foundationcommon/crmcommon/accelerators/automotive/BusinessFacility)|Physical facility or building where a business runs operations.  |
|[BusinessOperation](https://docs.microsoft.com/en-us/common-data-model/schema/core/applicationcommon/foundationcommon/crmcommon/accelerators/automotive/BusinessOperation)|Operation run at a business facility, such as new car sales showroom, used car sales or service center.  |
|[BusinessOperationCustomerPreference](https://docs.microsoft.com/en-us/common-data-model/schema/core/applicationcommon/foundationcommon/crmcommon/accelerators/automotive/BusinessOperationCustomerPreference)|Customer preference for a given type of business operation, such as preferred service center or rental depot.  |
|[BusinessType](https://docs.microsoft.com/en-us/common-data-model/schema/core/applicationcommon/foundationcommon/crmcommon/accelerators/automotive/BusinessType)|Type of business, such as national sales company, importer, distributor, dealer group or dealer.  |
|[ConfigurationCode](https://docs.microsoft.com/en-us/common-data-model/schema/core/applicationcommon/foundationcommon/crmcommon/accelerators/automotive/ConfigurationCode)|Unique OEM code for a given combination of configuration options.  |
|[ConfigurationOption](https://docs.microsoft.com/en-us/common-data-model/schema/core/applicationcommon/foundationcommon/crmcommon/accelerators/automotive/ConfigurationOption)|Configuration option included in devices with a given configuration code.  |
|[CustomerAttachment](https://docs.microsoft.com/en-us/common-data-model/schema/core/applicationcommon/foundationcommon/crmcommon/accelerators/automotive/CustomerAttachment)|Document or file related to a given customer or deal file.  |
|[CustomerIdentifier](https://docs.microsoft.com/en-us/common-data-model/schema/core/applicationcommon/foundationcommon/crmcommon/accelerators/automotive/CustomerIdentifier)|Unique identifier for a customer, such as customer number or manufacturers ID.  |
|[CustomerIdentifierType](https://docs.microsoft.com/en-us/common-data-model/schema/core/applicationcommon/foundationcommon/crmcommon/accelerators/automotive/CustomerIdentifierType)|Type of customer identifier, such as customer number or manufacturer ID.  |
|[Deal](https://docs.microsoft.com/en-us/common-data-model/schema/core/applicationcommon/foundationcommon/crmcommon/accelerators/automotive/Deal)|Business proposal for the sale of one or more vehicle or device, including optional trade-ins, add-ons and financial terms.  |
|[DealCustomer](https://docs.microsoft.com/en-us/common-data-model/schema/core/applicationcommon/foundationcommon/crmcommon/accelerators/automotive/DealCustomer)|Customer associated with a given deal.  |
|[DealDevice](https://docs.microsoft.com/en-us/common-data-model/schema/core/applicationcommon/foundationcommon/crmcommon/accelerators/automotive/DealDevice)|Vehicle or device that is the subject of a deal, which may involve one or more vehicle or device.  |
|[DealDeviceAddOn](https://docs.microsoft.com/en-us/common-data-model/schema/core/applicationcommon/foundationcommon/crmcommon/accelerators/automotive/DealDeviceAddOn)|Additional product or service offered with a given vehicle or device in a deal.  |
|[DealerPlate](https://docs.microsoft.com/en-us/common-data-model/schema/core/applicationcommon/foundationcommon/crmcommon/accelerators/automotive/DealerPlate)|License plate applied temporarily to vehicles to provide services such as test drives.  |
|[DealerPlateDeviceAssignment](https://docs.microsoft.com/en-us/common-data-model/schema/core/applicationcommon/foundationcommon/crmcommon/accelerators/automotive/DealerPlateDeviceAssignment)|Record of which dealer plates were used on which vehicle or device over time.  |
|[DealFile](https://docs.microsoft.com/en-us/common-data-model/schema/core/applicationcommon/foundationcommon/crmcommon/accelerators/automotive/DealFile)|Container for deals relating to a given opportunity.  |
|[DealTerm](https://docs.microsoft.com/en-us/common-data-model/schema/core/applicationcommon/foundationcommon/crmcommon/accelerators/automotive/DealTerm)|Terms applicable a given type of deal.  |
|[DealType](https://docs.microsoft.com/en-us/common-data-model/schema/core/applicationcommon/foundationcommon/crmcommon/accelerators/automotive/DealType)|Type of deal, such as new car sales, used car sales, heavy equipment sales, and so on.  |
|[Device](https://docs.microsoft.com/en-us/common-data-model/schema/core/applicationcommon/foundationcommon/crmcommon/accelerators/automotive/Device)|Physical piece of equipment of considerable value such as a vehicle or a device such as an excavator, that can be tracked through its entire life cycle of trade, ownership and service and may be related to one or more customers over time.  |
|[DeviceBrand](https://docs.microsoft.com/en-us/common-data-model/schema/core/applicationcommon/foundationcommon/crmcommon/accelerators/automotive/DeviceBrand)|Brand name of a vehicle or device manufacturer, main vendor for a group of devices or manufacturer or main vendor for supplier items.  |
|[DeviceClass](https://docs.microsoft.com/en-us/common-data-model/schema/core/applicationcommon/foundationcommon/crmcommon/accelerators/automotive/DeviceClass)|Family of vehicles or devices for the specific brand provided by the manufacturer.  |
|[DeviceComponent](https://docs.microsoft.com/en-us/common-data-model/schema/core/applicationcommon/foundationcommon/crmcommon/accelerators/automotive/DeviceComponent)|Physical or logical part of a vehicle or device.  |
|[DeviceGeneration](https://docs.microsoft.com/en-us/common-data-model/schema/core/applicationcommon/foundationcommon/crmcommon/accelerators/automotive/DeviceGeneration)|Specific period in the evolution of a device class over time.  |
|[DeviceInspection](https://docs.microsoft.com/en-us/common-data-model/schema/core/applicationcommon/foundationcommon/crmcommon/accelerators/automotive/DeviceInspection)|Record of inspections carried out on a given vehicle or device over time.  |
|[DeviceInspectionChecklist](https://docs.microsoft.com/en-us/common-data-model/schema/core/applicationcommon/foundationcommon/crmcommon/accelerators/automotive/DeviceInspectionChecklist)|Specific checklist of a given type, such as a pre-delivery inspection or a checklist used for a specific type of service.  |
|[DeviceInspectionChecklistType](https://docs.microsoft.com/en-us/common-data-model/schema/core/applicationcommon/foundationcommon/crmcommon/accelerators/automotive/DeviceInspectionChecklistType)|Type of checklist, such as pre-delivery or service.  |
|[DeviceLicensePlate](https://docs.microsoft.com/en-us/common-data-model/schema/core/applicationcommon/foundationcommon/crmcommon/accelerators/automotive/DeviceLicensePlate)|Record of license plates assigned to a given vehicle or device over time.  |
|[DeviceMeasure](https://docs.microsoft.com/en-us/common-data-model/schema/core/applicationcommon/foundationcommon/crmcommon/accelerators/automotive/DeviceMeasure)|Specific measurable quantity related to a vehicle or device that is used to track usage over time, such as miles driven, engine hours or time since purchase.  |
|[DeviceMeasurement](https://docs.microsoft.com/en-us/common-data-model/schema/core/applicationcommon/foundationcommon/crmcommon/accelerators/automotive/DeviceMeasurement)|Record of usage measurements for a given vehicle or device over time.  |
|[DeviceMeter](https://docs.microsoft.com/en-us/common-data-model/schema/core/applicationcommon/foundationcommon/crmcommon/accelerators/automotive/DeviceMeter)|Usage meter attached to a specific vehicle or device, such as odometer or fuel gauge.  |
|[DeviceModel](https://docs.microsoft.com/en-us/common-data-model/schema/core/applicationcommon/foundationcommon/crmcommon/accelerators/automotive/DeviceModel)|Sub-type of a device class, which may be identified by specific engine option, body styles and other common characteristics. Breaks down further into device model codes.  |
|[DeviceModelCode](https://docs.microsoft.com/en-us/common-data-model/schema/core/applicationcommon/foundationcommon/crmcommon/accelerators/automotive/DeviceModelCode)|Specific configuration of a device, such as a vehicle of specific generation, body style, engine option and transmission.  |
|[DeviceObservation](https://docs.microsoft.com/en-us/common-data-model/schema/core/applicationcommon/foundationcommon/crmcommon/accelerators/automotive/DeviceObservation)|Important observation on the state of a given vehicle or device, typically resulting from an inspection.  |
|[DeviceObservationType](https://docs.microsoft.com/en-us/common-data-model/schema/core/applicationcommon/foundationcommon/crmcommon/accelerators/automotive/DeviceObservationType)|Type of observation, indicating severity and nature of the observation and typically used for classification and filtering of observations.  |
|[DeviceRegistration](https://docs.microsoft.com/en-us/common-data-model/schema/core/applicationcommon/foundationcommon/crmcommon/accelerators/automotive/DeviceRegistration)|Record of registrations of a specific vehicle or device to specific customers over time.  |
|[DeviceSensor](https://docs.microsoft.com/en-us/common-data-model/schema/core/applicationcommon/foundationcommon/crmcommon/accelerators/automotive/DeviceSensor)|Sensor attached to or as part of a vehicle or device. May provide signals of device health or usage.  |
|[DeviceState](https://docs.microsoft.com/en-us/common-data-model/schema/core/applicationcommon/foundationcommon/crmcommon/accelerators/automotive/DeviceState)|Describes state of a vehicle or device, such as New, Used or Scrapped.  |
|[DeviceStyle](https://docs.microsoft.com/en-us/common-data-model/schema/core/applicationcommon/foundationcommon/crmcommon/accelerators/automotive/DeviceStyle)|Distinctive form or type of vehicle or device such as sedan or station wagon car, wheeled or crawler excavator, and so on.  |
|[DeviceType](https://docs.microsoft.com/en-us/common-data-model/schema/core/applicationcommon/foundationcommon/crmcommon/accelerators/automotive/DeviceType)|Fundamental type of device, such as vehicle, truck, harvester, boat engine, and so on.  |
|[DeviceVariant](https://docs.microsoft.com/en-us/common-data-model/schema/core/applicationcommon/foundationcommon/crmcommon/accelerators/automotive/DeviceVariant)|Standard variant of a device model code, with special characteristics such as a specific OEM-fitted accessory package or being a limited edition.  |
|[DeviceWarranty](https://docs.microsoft.com/en-us/common-data-model/schema/core/applicationcommon/foundationcommon/crmcommon/accelerators/automotive/DeviceWarranty)|Relationship indicating that a specific warranty applies to a specific vehicle or device.  |
|[DeviceWarrantyLimit](https://docs.microsoft.com/en-us/common-data-model/schema/core/applicationcommon/foundationcommon/crmcommon/accelerators/automotive/DeviceWarrantyLimit)|Limits of a specific warranty on a specific vehicle or device, such as maximum mileage or specific expiration date.  |
|[FinancingOpportunity](https://docs.microsoft.com/en-us/common-data-model/schema/core/applicationcommon/foundationcommon/crmcommon/accelerators/automotive/FinancingOpportunity)|Financing opportunity associated with a specific vehicle or device included in a lead.  |
|[FinancingOpportunityDetail](https://docs.microsoft.com/en-us/common-data-model/schema/core/applicationcommon/foundationcommon/crmcommon/accelerators/automotive/FinancingOpportunityDetail)|Type of payment that forms part of a financing opportunity.  |
|[Fleet](https://docs.microsoft.com/en-us/common-data-model/schema/core/applicationcommon/foundationcommon/crmcommon/accelerators/automotive/Fleet)|Collection of devices belonging to a specific customer or business operation, typically serving a specific purpose.  |
|[FleetDevice](https://docs.microsoft.com/en-us/common-data-model/schema/core/applicationcommon/foundationcommon/crmcommon/accelerators/automotive/FleetDevice)|Represents a vehicle or device as part of a specific fleet.  |
|[Lead](https://docs.microsoft.com/en-us/common-data-model/schema/core/applicationcommon/foundationcommon/crmcommon/accelerators/automotive/Lead)|A prospect or a potential sales opportunity. Leads are converted into accounts, contacts, or opportunities when they're qualified. Otherwise, they're deleted or archived.  |
|[LeadDevice](https://docs.microsoft.com/en-us/common-data-model/schema/core/applicationcommon/foundationcommon/crmcommon/accelerators/automotive/LeadDevice)|Vehicle or device that is the subject of a lead, which may involve one or more vehicles or devices.  |
|[LeadDeviceSpecification](https://docs.microsoft.com/en-us/common-data-model/schema/core/applicationcommon/foundationcommon/crmcommon/accelerators/automotive/LeadDeviceSpecification)|Loose description of a characteristic of a vehicle or device of interest in a lead.  |
|[LeadDisposition](https://docs.microsoft.com/en-us/common-data-model/schema/core/applicationcommon/foundationcommon/crmcommon/accelerators/automotive/LeadDisposition)|Record of activities performed to follow up and nurture a lead over time.  |
|[LeadDispositionActivity](https://docs.microsoft.com/en-us/common-data-model/schema/core/applicationcommon/foundationcommon/crmcommon/accelerators/automotive/LeadDispositionActivity)|Specific activity that should be taken to follow up and nurture a lead.  |
|[LeadPriceType](https://docs.microsoft.com/en-us/common-data-model/schema/core/applicationcommon/foundationcommon/crmcommon/accelerators/automotive/LeadPriceType)|Type of price tag for a vehicle or device, such as MSRP, appraisal or asking price.  |
|[LeadProspect](https://docs.microsoft.com/en-us/common-data-model/schema/core/applicationcommon/foundationcommon/crmcommon/accelerators/automotive/LeadProspect)|Contact associated with a given lead.  |
|[LeadSpecificationType](https://docs.microsoft.com/en-us/common-data-model/schema/core/applicationcommon/foundationcommon/crmcommon/accelerators/automotive/LeadSpecificationType)|Type of characteristic used to loosely describe a vehicle or device of interest in a lead.  |
|[OperationCode](https://docs.microsoft.com/en-us/common-data-model/schema/core/applicationcommon/foundationcommon/crmcommon/accelerators/automotive/OperationCode)|Standard operation performed during service, typically specified by the vehicle or device manufacturer.  |
|[OperationType](https://docs.microsoft.com/en-us/common-data-model/schema/core/applicationcommon/foundationcommon/crmcommon/accelerators/automotive/OperationType)|Type of business operation, such as new car sales showroom, used car sales or service center.  |
|[SalesContract](https://docs.microsoft.com/en-us/common-data-model/schema/core/applicationcommon/foundationcommon/crmcommon/accelerators/automotive/SalesContract)|Contract involving the sale of one or more vehicle or device to a customer.  |
|[SalesContractDetail](https://docs.microsoft.com/en-us/common-data-model/schema/core/applicationcommon/foundationcommon/crmcommon/accelerators/automotive/SalesContractDetail)|Vehicle or device included in a sales contract.  |
|[SalesContractPayment](https://docs.microsoft.com/en-us/common-data-model/schema/core/applicationcommon/foundationcommon/crmcommon/accelerators/automotive/SalesContractPayment)|Payment made in accordance with a sales contract.  |
|[SalesContractTerm](https://docs.microsoft.com/en-us/common-data-model/schema/core/applicationcommon/foundationcommon/crmcommon/accelerators/automotive/SalesContractTerm)|Terms applicable a given type of sales contract.  |
|[SalesContractType](https://docs.microsoft.com/en-us/common-data-model/schema/core/applicationcommon/foundationcommon/crmcommon/accelerators/automotive/SalesContractType)|Type of sales contract, such as new car sales, used car sales, heavy equipment sales, and so on.  |
|[ServiceAppointment](https://docs.microsoft.com/en-us/common-data-model/schema/core/applicationcommon/foundationcommon/crmcommon/accelerators/automotive/ServiceAppointment)|Record of service appointments for a specific vehicle or device over time.  |
|[ServiceAppointmentType](https://docs.microsoft.com/en-us/common-data-model/schema/core/applicationcommon/foundationcommon/crmcommon/accelerators/automotive/ServiceAppointmentType)|Type of service appointment.  |
|[ServiceContract](https://docs.microsoft.com/en-us/common-data-model/schema/core/applicationcommon/foundationcommon/crmcommon/accelerators/automotive/ServiceContract)|Contract involving the service of one or more vehicles or devices owned by a customer.  |
|[ServiceContractDetail](https://docs.microsoft.com/en-us/common-data-model/schema/core/applicationcommon/foundationcommon/crmcommon/accelerators/automotive/ServiceContractDetail)|Vehicle or device included in a service contract.  |
|[ServiceContractTerm](https://docs.microsoft.com/en-us/common-data-model/schema/core/applicationcommon/foundationcommon/crmcommon/accelerators/automotive/ServiceContractTerm)|Terms applicable a given type of service contract.  |
|[ServiceContractType](https://docs.microsoft.com/en-us/common-data-model/schema/core/applicationcommon/foundationcommon/crmcommon/accelerators/automotive/ServiceContractType)|Type of service contract.  |
|[ServiceOrder](https://docs.microsoft.com/en-us/common-data-model/schema/core/applicationcommon/foundationcommon/crmcommon/accelerators/automotive/ServiceOrder)|Service order for a specific vehicle or device.  |
|[ServiceOrderGroup](https://docs.microsoft.com/en-us/common-data-model/schema/core/applicationcommon/foundationcommon/crmcommon/accelerators/automotive/ServiceOrderGroup)|Group of service orders.  |
|[ServiceOrderJob](https://docs.microsoft.com/en-us/common-data-model/schema/core/applicationcommon/foundationcommon/crmcommon/accelerators/automotive/ServiceOrderJob)|Job performed during the execution of a service order. A single service order may require one or more jobs to be completed.  |
|[ServiceOrderJobDetail](https://docs.microsoft.com/en-us/common-data-model/schema/core/applicationcommon/foundationcommon/crmcommon/accelerators/automotive/ServiceOrderJobDetail)|Record of time, material or other information relating to the execution of a given service order job.  |
|[ServiceOrderJobType](https://docs.microsoft.com/en-us/common-data-model/schema/core/applicationcommon/foundationcommon/crmcommon/accelerators/automotive/ServiceOrderJobType)|Type of service job that is performed frequently and should follow a standard procedure.  |
|[ServiceOrderType](https://docs.microsoft.com/en-us/common-data-model/schema/core/applicationcommon/foundationcommon/crmcommon/accelerators/automotive/ServiceOrderType)|Type of service order.  |
|[Specification](https://docs.microsoft.com/en-us/common-data-model/schema/core/applicationcommon/foundationcommon/crmcommon/accelerators/automotive/Specification)|Specification of a vehicle or device with a given combination of configuration options and accessories.  |
|[SpecificationAccessory](https://docs.microsoft.com/en-us/common-data-model/schema/core/applicationcommon/foundationcommon/crmcommon/accelerators/automotive/SpecificationAccessory)|Optional accessories that are included on a vehicle or device with the given specification.  |
|[SpecificationAttribute](https://docs.microsoft.com/en-us/common-data-model/schema/core/applicationcommon/foundationcommon/crmcommon/accelerators/automotive/SpecificationAttribute)|Technical specifications are represented as a grouped list of attribute types that collectively describe key characteristics of a given vehicle or device.  |
|[TestDrive](https://docs.microsoft.com/en-us/common-data-model/schema/core/applicationcommon/foundationcommon/crmcommon/accelerators/automotive/TestDrive)|The physical experience a customer or prospect has of a vehicle or device prior to a possible purchase of same or similar one.  |
|[TradeIn](https://docs.microsoft.com/en-us/common-data-model/schema/core/applicationcommon/foundationcommon/crmcommon/accelerators/automotive/TradeIn)|Vehicle or device that a customer wants to use as part of payment buying another one (new or used).  |
|[Unit](https://docs.microsoft.com/en-us/common-data-model/schema/core/applicationcommon/foundationcommon/crmcommon/accelerators/automotive/Unit)|Unit of measure.  |
|[Warranty](https://docs.microsoft.com/en-us/common-data-model/schema/core/applicationcommon/foundationcommon/crmcommon/accelerators/automotive/Warranty)|Contract between a vehicle or device manufacturer, importer, dealer and end customer, promising a certain quality level for a given amount of time or usage.  |
|[WarrantyLimit](https://docs.microsoft.com/en-us/common-data-model/schema/core/applicationcommon/foundationcommon/crmcommon/accelerators/automotive/WarrantyLimit)|Limits to a specific warranty, such as maximum mileage or time until expiration.  |
|[WarrantyType](https://docs.microsoft.com/en-us/common-data-model/schema/core/applicationcommon/foundationcommon/crmcommon/accelerators/automotive/WarrantyType)|Types of warranties, such as standard or extended.  |