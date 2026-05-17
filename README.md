
<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Royole Corporation Bankruptcy Case Study</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
    <style>
        body {
            font-family: 'Inter', -apple-system, BlinkMacSystemFont, sans-serif;
            background-color: #FFFFFF;
        }
        .card {
            background-color: white;
            border: 1px solid #E5E7EB;
            border-radius: 1.25rem;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.05);
            transition: all 0.3s cubic-bezier(0.25, 0.8, 0.25, 1);
            overflow: hidden;
            position: relative;
        }
        .card:hover {
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.1);
        }
        .highlight-gradient-blue {
            background: linear-gradient(135deg, rgba(59, 130, 246, 0), rgba(59, 130, 246, 0.05));
        }
        .highlight-gradient-red {
            background: linear-gradient(135deg, rgba(239, 68, 68, 0), rgba(239, 68, 68, 0.05));
        }
        .highlight-gradient-green {
            background: linear-gradient(135deg, rgba(16, 185, 129, 0), rgba(16, 185, 129, 0.05));
        }
        .highlight-gradient-purple {
            background: linear-gradient(135deg, rgba(139, 92, 246, 0), rgba(139, 92, 246, 0.05));
        }
        .highlight-gradient-orange {
            background: linear-gradient(135deg, rgba(249, 115, 22, 0), rgba(249, 115, 22, 0.05));
        }
        .highlight-gradient-teal {
            background: linear-gradient(135deg, rgba(20, 184, 166, 0), rgba(20, 184, 166, 0.05));
        }
        .text-gradient-blue {
            background-image: linear-gradient(to right, #3B82F6, #60A5FA);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        .text-gradient-red {
            background-image: linear-gradient(to right, #EF4444, #F87171);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        .text-gradient-green {
            background-image: linear-gradient(to right, #10B981, #34D399);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        .text-gradient-purple {
            background-image: linear-gradient(to right, #8B5CF6, #A78BFA);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        .text-gradient-orange {
            background-image: linear-gradient(to right, #F97316, #FB923C);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
    </style>
</head>
<body class="bg-white">
    <div class="max-w-7xl mx-auto p-4 md:p-8">
        <div class="grid grid-cols-1 md:grid-cols-4 gap-4 md:gap-6">
            
            <!-- Title Card -->
            <div class="card md:col-span-4 p-8 flex flex-col justify-center items-center text-center">
                <div class="absolute top-0 left-0 w-full h-full highlight-gradient-blue"></div>
                <div class="relative z-10">
                    <div class="text-5xl md:text-7xl font-bold text-gray-800 mb-4">Royole Corporation</div>
                    <div class="text-xl md:text-2xl text-gray-500 mb-2">柔宇科技 | Bankruptcy Case Study</div>
                    <div class="w-24 h-1 bg-gradient-to-r from-blue-500 to-blue-300 mx-auto rounded-full"></div>
                </div>
            </div>

            <!-- Executive Summary Card -->
            <div class="card md:col-span-2 md:row-span-2 p-8 flex flex-col">
                <div class="absolute top-0 left-0 w-full h-full highlight-gradient-red"></div>
                <div class="relative z-10 flex flex-col flex-grow">
                    <div class="flex items-center mb-6">
                        <i class="fa-solid fa-file-circle-exclamation text-3xl text-red-500 mr-4"></i>
                        <h2 class="text-2xl font-bold text-gray-800">Executive Summary</h2>
                    </div>
                    <div class="flex-grow space-y-4 text-gray-600">
                        <p>Royole Corporation, once a <span class="font-bold text-red-600">50 billion RMB</span> valued unicorn in China's flexible display technology sector, was officially declared bankrupt on <span class="font-bold">November 18, 2024</span>.</p>
                        <p>Founded in 2012 with just 100,000 RMB, the company initially gained global recognition for developing the world's thinnest flexible display at just <span class="font-bold text-red-600">0.01mm thickness</span>.</p>
                        <p>Despite technological breakthroughs and massive investments exceeding <span class="font-bold text-red-600">10 billion RMB</span>, Royole failed to achieve commercial success, accumulating <span class="font-bold text-red-600">3.195 billion RMB in losses</span> while generating only <span class="font-bold text-red-600">517 million RMB in revenue</span> from 2017 to 2020.</p>
                    </div>
                    <div class="mt-6 p-4 bg-red-50 rounded-lg border-l-4 border-red-500">
                        <p class="text-sm font-medium text-red-700">The company's collapse serves as a critical case study in anti-crisis management, highlighting the dangers of misaligned technical strategies, poor corporate governance, and unsustainable financial models.</p>
                    </div>
                </div>
            </div>

            <!-- Key Timeline Card -->
            <div class="card md:col-span-2 p-8 flex flex-col">
                <div class="absolute top-0 left-0 w-full h-full highlight-gradient-green"></div>
                <div class="relative z-10">
                    <div class="flex items-center mb-6">
                        <i class="fa-solid fa-timeline text-3xl text-green-500 mr-4"></i>
                        <h2 class="text-2xl font-bold text-gray-800">Key Timeline</h2>
                    </div>
                    <div class="space-y-4">
                        <div class="flex items-start">
                            <div class="flex-shrink-0 w-20 text-sm font-medium text-green-600">2012</div>
                            <div class="text-gray-600">Founded by Liu Zihong with 100,000 RMB investment</div>
                        </div>
                        <div class="flex items-start">
                            <div class="flex-shrink-0 w-20 text-sm font-medium text-green-600">2014</div>
                            <div class="text-gray-600">Developed world's thinnest flexible display (0.01mm)</div>
                        </div>
                        <div class="flex items-start">
                            <div class="flex-shrink-0 w-20 text-sm font-medium text-green-600">2018</div>
                            <div class="text-gray-600">Launched FlexPai, world's first foldable smartphone</div>
                        </div>
                        <div class="flex items-start">
                            <div class="flex-shrink-0 w-20 text-sm font-medium text-green-600">2021</div>
                            <div class="text-gray-600">Voluntarily withdrew IPO application from STAR Market</div>
                        </div>
                        <div class="flex items-start">
                            <div class="flex-shrink-0 w-20 text-sm font-medium text-green-600">2024</div>
                            <div class="text-gray-600">Officially declared bankrupt by Shenzhen Intermediate People's Court</div>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Funding & Valuation Card -->
            <div class="card md:col-span-2 p-8 flex flex-col">
                <div class="absolute top-0 left-0 w-full h-full highlight-gradient-purple"></div>
                <div class="relative z-10 flex flex-col h-full">
                    <div class="flex items-center mb-6">
                        <i class="fa-solid fa-chart-line text-3xl text-purple-500 mr-4"></i>
                        <h2 class="text-2xl font-bold text-gray-800">Funding & Valuation</h2>
                    </div>
                    <div class="flex-grow relative h-64">
                        <canvas id="valuationChart"></canvas>
                    </div>
                    <div class="mt-4 grid grid-cols-2 gap-4 text-center">
                        <div class="p-3 bg-purple-50 rounded-lg">
                            <div class="text-2xl font-bold text-gradient-purple">10+</div>
                            <div class="text-sm text-gray-500">Billion RMB Raised</div>
                        </div>
                        <div class="p-3 bg-purple-50 rounded-lg">
                            <div class="text-2xl font-bold text-gradient-purple">9</div>
                            <div class="text-sm text-gray-500">Funding Rounds</div>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Financial Performance Card -->
            <div class="card md:col-span-4 p-8 flex flex-col">
                <div class="absolute top-0 left-0 w-full h-full highlight-gradient-blue"></div>
                <div class="relative z-10">
                    <div class="flex items-center mb-6">
                        <i class="fa-solid fa-sack-dollar text-3xl text-blue-500 mr-4"></i>
                        <h2 class="text-2xl font-bold text-gray-800">Financial Performance (2017-2020)</h2>
                    </div>
                    <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                        <div class="h-64">
                            <canvas id="revenueChart"></canvas>
                        </div>
                        <div class="h-64">
                            <canvas id="profitChart"></canvas>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Capacity Utilization Card -->
            <div class="card md:col-span-2 p-8 flex flex-col">
                <div class="absolute top-0 left-0 w-full h-full highlight-gradient-orange"></div>
                <div class="relative z-10">
                    <div class="flex items-center mb-6">
                        <i class="fa-solid fa-industry text-3xl text-orange-500 mr-4"></i>
                        <h2 class="text-2xl font-bold text-gray-800">Capacity Utilization</h2>
                    </div>
                    <div class="h-64">
                        <canvas id="capacityChart"></canvas>
                    </div>
                    <div class="mt-4 p-4 bg-orange-50 rounded-lg">
                        <p class="text-sm text-gray-600">The expensive production line operated at extremely low efficiency, with capacity utilization plummeting to <span class="font-bold text-orange-600">5.3%</span> in H1 2020.</p>
                    </div>
                </div>
            </div>

            <!-- Employee Reduction Card -->
            <div class="card md:col-span-2 p-8 flex flex-col">
                <div class="absolute top-0 left-0 w-full h-full highlight-gradient-teal"></div>
                <div class="relative z-10">
                    <div class="flex items-center mb-6">
                        <i class="fa-solid fa-users-slash text-3xl text-teal-500 mr-4"></i>
                        <h2 class="text-2xl font-bold text-gray-800">Employee Reduction</h2>
                    </div>
                    <div class="h-64">
                        <canvas id="employeeChart"></canvas>
                    </div>
                    <div class="mt-4 p-4 bg-teal-50 rounded-lg">
                        <p class="text-sm text-gray-600">Employee numbers dropped from over <span class="font-bold text-teal-600">2,000</span> in H1 2020 to just <span class="font-bold text-teal-600">73</span> in 2023, representing a <span class="font-bold text-teal-600">96%+</span> layoff rate.</p>
                    </div>
                </div>
            </div>

            <!-- Key Factors Card -->
            <div class="card md:col-span-4 p-8">
                <div class="absolute top-0 left-0 w-full h-full highlight-gradient-red"></div>
                <div class="relative z-10">
                    <div class="flex items-center mb-6">
                        <i class="fa-solid fa-magnifying-glass-chart text-3xl text-red-500 mr-4"></i>
                        <h2 class="text-2xl font-bold text-gray-800">Key Bankruptcy Factors</h2>
                    </div>
                    <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                        <div class="space-y-4">
                            <div class="p-4 border-l-4 border-red-500 bg-red-50">
                                <h3 class="font-bold text-gray-800 mb-2">Internal Management Factors</h3>
                                <ul class="text-sm text-gray-600 space-y-1">
                                    <li>• Founder's capability mismatch (scientist vs. business manager)</li>
                                    <li>• Corporate governance flaws (38.6% equity but 72% voting rights)</li>
                                    <li>• Rigid decision-making mechanism</li>
                                    <li>• Failed oversight mechanisms</li>
                                </ul>
                            </div>
                            <div class="p-4 border-l-4 border-red-500 bg-red-50">
                                <h3 class="font-bold text-gray-800 mb-2">Technology Route Errors</h3>
                                <ul class="text-sm text-gray-600 space-y-1">
                                    <li>• Deviation from mainstream LTPS technology</li>
                                    <li>• Severe disconnection between technology and business</li>
                                    <li>• Incompatible with mature supplier systems</li>
                                    <li>• High R&D, equipment and material costs</li>
                                </ul>
                            </div>
                        </div>
                        <div class="space-y-4">
                            <div class="p-4 border-l-4 border-red-500 bg-red-50">
                                <h3 class="font-bold text-gray-800 mb-2">Imbalanced Financial Structure</h3>
                                <ul class="text-sm text-gray-600 space-y-1">
                                    <li>• Excessive reliance on external financing</li>
                                    <li>• Inefficient capital utilization</li>
                                    <li>• Out-of-control production line investment (11B RMB)</li>
                                    <li>• Poor cash chain management</li>
                                </ul>
                            </div>
                            <div class="p-4 border-l-4 border-red-500 bg-red-50">
                                <h3 class="font-bold text-gray-800 mb-2">External Environmental Factors</h3>
                                <ul class="text-sm text-gray-600 space-y-1">
                                    <li>• Cooling of capital markets after 2021</li>
                                    <li>• Chain reaction of IPO failure</li>
                                    <li>• Investors focusing more on profitability</li>
                                    <li>• Impact of "capital winter"</li>
                                </ul>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Strategic Mistakes Card -->
            <div class="card md:col-span-4 p-8">
                <div class="absolute top-0 left-0 w-full h-full highlight-gradient-purple"></div>
                <div class="relative z-10">
                    <div class="flex items-center mb-6">
                        <i class="fa-solid fa-chess-king text-3xl text-purple-500 mr-4"></i>
                        <h2 class="text-2xl font-bold text-gray-800">Critical Strategic Mistakes</h2>
                    </div>
                    <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
                        <div class="bg-purple-50 p-6 rounded-lg border border-purple-100">
                            <div class="text-4xl text-purple-500 mb-4"><i class="fa-solid fa-handshake-slash"></i></div>
                            <h3 class="font-bold text-gray-800 mb-2">Refusal of Partnerships</h3>
                            <p class="text-sm text-gray-600">Declined opportunities to partner with Huawei and other industry giants, choosing instead to pursue a "full industrial chain giant dream."</p>
                        </div>
                        <div class="bg-purple-50 p-6 rounded-lg border border-purple-100">
                            <div class="text-4xl text-purple-500 mb-4"><i class="fa-solid fa-building-columns"></i></div>
                            <h3 class="font-bold text-gray-800 mb-2">Building Own Production Line</h3>
                            <p class="text-sm text-gray-600">Invested 11B RMB to build a proprietary production line, blocking potential patent cooperation with Samsung and BOE.</p>
                        </div>
                        <div class="bg-purple-50 p-6 rounded-lg border border-purple-100">
                            <div class="text-4xl text-purple-500 mb-4"><i class="fa-solid fa-arrow-trend-down"></i></div>
                            <h3 class="font-bold text-gray-800 mb-2">IPO Failure</h3>
                            <p class="text-sm text-gray-600">Voluntarily withdrew IPO application in 2021, sending negative signals to the market and making subsequent financing nearly impossible.</p>
                        </div>
                    </div>
                </div>
            </div>

        </div>
    </div>
</body>
<script>
    // Valuation Chart
    const valuationCtx = document.getElementById('valuationChart').getContext('2d');
    new Chart(valuationCtx, {
        type: 'line',
        data: {
            labels: ['2012', '2013', '2015', '2016', '2017', '2018', '2020'],
            datasets: [{
                label: 'Company Valuation (Billion RMB)',
                data: [0.001, 0.1, 1.1, 1.6, 50, 50, 57.7],
                borderColor: '#8B5CF6',
                backgroundColor: 'rgba(139, 92, 246, 0.1)',
                borderWidth: 3,
                fill: true,
                tension: 0.4
            }]
        },
        options: {
            responsive: true,
            maintainAspectRatio: false,
            plugins: {
                legend: {
                    display: false
                }
            },
            scales: {
                y: {
                    beginAtZero: true,
                    grid: {
                        color: 'rgba(0, 0, 0, 0.05)'
                    }
                },
                x: {
                    grid: {
                        display: false
                    }
                }
            }
        }
    });

    // Revenue Chart
    const revenueCtx = document.getElementById('revenueChart').getContext('2d');
    new Chart(revenueCtx, {
        type: 'bar',
        data: {
            labels: ['2017', '2018', '2019', 'H1 2020'],
            datasets: [{
                label: 'Revenue (Billion RMB)',
                data: [0.65, 1.09, 2.27, 1.16],
                backgroundColor: [
                    'rgba(59, 130, 246, 0.7)',
                    'rgba(59, 130, 246, 0.7)',
                    'rgba(59, 130, 246, 0.7)',
                    'rgba(59, 130, 246, 0.7)'
                ],
                borderColor: [
                    'rgba(59, 130, 246, 1)',
                    'rgba(59, 130, 246, 1)',
                    'rgba(59, 130, 246, 1)',
                    'rgba(59, 130, 246, 1)'
                ],
                borderWidth: 1
            }]
        },
        options: {
            responsive: true,
            maintainAspectRatio: false,
            plugins: {
                title: {
                    display: true,
                    text: 'Revenue Growth (2017-2020)',
                    font: {
                        size: 16
                    }
                },
                legend: {
                    display: false
                }
            },
            scales: {
                y: {
                    beginAtZero: true,
                    grid: {
                        color: 'rgba(0, 0, 0, 0.05)'
                    }
                },
                x: {
                    grid: {
                        display: false
                    }
                }
            }
        }
    });

    // Profit Chart
    const profitCtx = document.getElementById('profitChart').getContext('2d');
    new Chart(profitCtx, {
        type: 'bar',
        data: {
            labels: ['2017', '2018', '2019', 'H1 2020'],
            datasets: [{
                label: 'Net Profit (Billion RMB)',
                data: [-3.59, -8.02, -10.73, -9.61],
                backgroundColor: [
                    'rgba(239, 68, 68, 0.7)',
                    'rgba(239, 68, 68, 0.7)',
                    'rgba(239, 68, 68, 0.7)',
                    'rgba(239, 68, 68, 0.7)'
                ],
                borderColor: [
                    'rgba(239, 68, 68, 1)',
                    'rgba(239, 68, 68, 1)',
                    'rgba(239, 68, 68, 1)',
                    'rgba(239, 68, 68, 1)'
                ],
                borderWidth: 1
            }]
        },
        options: {
            responsive: true,
            maintainAspectRatio: false,
            plugins: {
                title: {
                    display: true,
                    text: 'Net Losses (2017-2020)',
                    font: {
                        size: 16
                    }
                },
                legend: {
                    display: false
                }
            },
            scales: {
                y: {
                    grid: {
                        color: 'rgba(0, 0, 0, 0.05)'
                    }
                },
                x: {
                    grid: {
                        display: false
                    }
                }
            }
        }
    });

    // Capacity Utilization Chart
    const capacityCtx = document.getElementById('capacityChart').getContext('2d');
    new Chart(capacityCtx, {
        type: 'bar',
        data: {
            labels: ['2018', '2019', 'H1 2020'],
            datasets: [{
                label: 'Capacity Utilization (%)',
                data: [15.1, 31.2, 5.3],
                backgroundColor: [
                    'rgba(249, 115, 22, 0.7)',
                    'rgba(249, 115, 22, 0.7)',
                    'rgba(249, 115, 22, 0.7)'
                ],
                borderColor: [
                    'rgba(249, 115, 22, 1)',
                    'rgba(249, 115, 22, 1)',
                    'rgba(249, 115, 22, 1)'
                ],
                borderWidth: 1
            }]
        },
        options: {
            responsive: true,
            maintainAspectRatio: false,
            plugins: {
                legend: {
                    display: false
                }
            },
            scales: {
                y: {
                    beginAtZero: true,
                    max: 100,
                    grid: {
                        color: 'rgba(0, 0, 0, 0.05)'
                    }
                },
                x: {
                    grid: {
                        display: false
                    }
                }
            }
        }
    });

    // Employee Reduction Chart
    const employeeCtx = document.getElementById('employeeChart').getContext('2d');
    new Chart(employeeCtx, {
        type: 'line',
        data: {
            labels: ['H1 2020', 'Mar 2022', '2023'],
            datasets: [{
                label: 'Total Employees',
                data: [2000, 700, 73],
                borderColor: '#14B8A6',
                backgroundColor: 'rgba(20, 184, 166, 0.1)',
                borderWidth: 3,
                fill: true,
                tension: 0.1
            }]
        },
        options: {
            responsive: true,
            maintainAspectRatio: false,
            plugins: {
                legend: {
                    display: false
                }
            },
            scales: {
                y: {
                    beginAtZero: true,
                    grid: {
                        color: 'rgba(0, 0, 0, 0.05)'
                    }
                },
                x: {
                    grid: {
                        display: false
                    }
                }
            }
        }
    });
</script>
</html>
