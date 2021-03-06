

RangeAttributeAdapter Class
===========================





Namespace
    :dn:ns:`Microsoft.AspNetCore.Mvc.DataAnnotations.Internal`
Assemblies
    * Microsoft.AspNetCore.Mvc.DataAnnotations

----

.. contents::
   :local:



Inheritance Hierarchy
---------------------


* :dn:cls:`System.Object`
* :dn:cls:`Microsoft.AspNetCore.Mvc.DataAnnotations.Internal.ValidationAttributeAdapter{System.ComponentModel.DataAnnotations.RangeAttribute}`
* :dn:cls:`Microsoft.AspNetCore.Mvc.DataAnnotations.Internal.AttributeAdapterBase{System.ComponentModel.DataAnnotations.RangeAttribute}`
* :dn:cls:`Microsoft.AspNetCore.Mvc.DataAnnotations.Internal.RangeAttributeAdapter`








Syntax
------

.. code-block:: csharp

    public class RangeAttributeAdapter : AttributeAdapterBase<RangeAttribute>, IAttributeAdapter, IClientModelValidator








.. dn:class:: Microsoft.AspNetCore.Mvc.DataAnnotations.Internal.RangeAttributeAdapter
    :hidden:

.. dn:class:: Microsoft.AspNetCore.Mvc.DataAnnotations.Internal.RangeAttributeAdapter

Constructors
------------

.. dn:class:: Microsoft.AspNetCore.Mvc.DataAnnotations.Internal.RangeAttributeAdapter
    :noindex:
    :hidden:

    
    .. dn:constructor:: Microsoft.AspNetCore.Mvc.DataAnnotations.Internal.RangeAttributeAdapter.RangeAttributeAdapter(System.ComponentModel.DataAnnotations.RangeAttribute, Microsoft.Extensions.Localization.IStringLocalizer)
    
        
    
        
        :type attribute: System.ComponentModel.DataAnnotations.RangeAttribute
    
        
        :type stringLocalizer: Microsoft.Extensions.Localization.IStringLocalizer
    
        
        .. code-block:: csharp
    
            public RangeAttributeAdapter(RangeAttribute attribute, IStringLocalizer stringLocalizer)
    

Methods
-------

.. dn:class:: Microsoft.AspNetCore.Mvc.DataAnnotations.Internal.RangeAttributeAdapter
    :noindex:
    :hidden:

    
    .. dn:method:: Microsoft.AspNetCore.Mvc.DataAnnotations.Internal.RangeAttributeAdapter.AddValidation(Microsoft.AspNetCore.Mvc.ModelBinding.Validation.ClientModelValidationContext)
    
        
    
        
        :type context: Microsoft.AspNetCore.Mvc.ModelBinding.Validation.ClientModelValidationContext
    
        
        .. code-block:: csharp
    
            public override void AddValidation(ClientModelValidationContext context)
    
    .. dn:method:: Microsoft.AspNetCore.Mvc.DataAnnotations.Internal.RangeAttributeAdapter.GetErrorMessage(Microsoft.AspNetCore.Mvc.ModelBinding.Validation.ModelValidationContextBase)
    
        
    
        
        :type validationContext: Microsoft.AspNetCore.Mvc.ModelBinding.Validation.ModelValidationContextBase
        :rtype: System.String
    
        
        .. code-block:: csharp
    
            public override string GetErrorMessage(ModelValidationContextBase validationContext)
    

