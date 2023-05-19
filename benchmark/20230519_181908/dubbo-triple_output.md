# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.104 ops/ms
# Warmup Iteration   2: 2.562 ops/ms
# Warmup Iteration   3: 5.130 ops/ms
Iteration   1: 5.633 ops/ms
Iteration   2: 5.798 ops/ms
Iteration   3: 5.743 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.725 ±(99.9%) 1.536 ops/ms [Average]
  (min, avg, max) = (5.633, 5.725, 5.798), stdev = 0.084
  CI (99.9%): [4.189, 7.261] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:16
# Fork: 1 of 1
# Warmup Iteration   1: 1.353 ops/ms
# Warmup Iteration   2: 4.456 ops/ms
# Warmup Iteration   3: 5.824 ops/ms
Iteration   1: 5.837 ops/ms
Iteration   2: 5.683 ops/ms
Iteration   3: 5.958 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.826 ±(99.9%) 2.514 ops/ms [Average]
  (min, avg, max) = (5.683, 5.826, 5.958), stdev = 0.138
  CI (99.9%): [3.312, 8.340] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:03
# Fork: 1 of 1
# Warmup Iteration   1: 1.571 ops/ms
# Warmup Iteration   2: 4.488 ops/ms
# Warmup Iteration   3: 5.554 ops/ms
Iteration   1: 5.307 ops/ms
Iteration   2: 5.667 ops/ms
Iteration   3: 5.577 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.517 ±(99.9%) 3.418 ops/ms [Average]
  (min, avg, max) = (5.307, 5.517, 5.667), stdev = 0.187
  CI (99.9%): [2.099, 8.935] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 1.465 ops/ms
# Warmup Iteration   2: 3.348 ops/ms
# Warmup Iteration   3: 4.538 ops/ms
Iteration   1: 4.644 ops/ms
Iteration   2: 4.828 ops/ms
Iteration   3: 4.689 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.720 ±(99.9%) 1.750 ops/ms [Average]
  (min, avg, max) = (4.644, 4.720, 4.828), stdev = 0.096
  CI (99.9%): [2.970, 6.470] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 21.314 ±(99.9%) 0.134 ms/op
# Warmup Iteration   2: 7.134 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 6.416 ±(99.9%) 0.012 ms/op
Iteration   1: 6.064 ±(99.9%) 0.011 ms/op
Iteration   2: 5.594 ±(99.9%) 0.017 ms/op
Iteration   3: 5.700 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.786 ±(99.9%) 4.495 ms/op [Average]
  (min, avg, max) = (5.594, 5.786, 6.064), stdev = 0.246
  CI (99.9%): [1.291, 10.280] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 19.277 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 6.387 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 5.453 ±(99.9%) 0.014 ms/op
Iteration   1: 5.495 ±(99.9%) 0.015 ms/op
Iteration   2: 5.408 ±(99.9%) 0.014 ms/op
Iteration   3: 5.408 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.437 ±(99.9%) 0.912 ms/op [Average]
  (min, avg, max) = (5.408, 5.437, 5.495), stdev = 0.050
  CI (99.9%): [4.525, 6.349] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 20.882 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 7.756 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 5.834 ±(99.9%) 0.009 ms/op
Iteration   1: 6.075 ±(99.9%) 0.008 ms/op
Iteration   2: 5.785 ±(99.9%) 0.028 ms/op
Iteration   3: 5.749 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.870 ±(99.9%) 3.260 ms/op [Average]
  (min, avg, max) = (5.749, 5.870, 6.075), stdev = 0.179
  CI (99.9%): [2.610, 9.130] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 20.977 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 8.687 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 6.710 ±(99.9%) 0.012 ms/op
Iteration   1: 6.658 ±(99.9%) 0.015 ms/op
Iteration   2: 6.587 ±(99.9%) 0.017 ms/op
Iteration   3: 6.611 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.619 ±(99.9%) 0.660 ms/op [Average]
  (min, avg, max) = (6.587, 6.619, 6.658), stdev = 0.036
  CI (99.9%): [5.959, 7.279] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 19.398 ±(99.9%) 0.324 ms/op
# Warmup Iteration   2: 7.687 ±(99.9%) 0.061 ms/op
# Warmup Iteration   3: 6.155 ±(99.9%) 0.027 ms/op
Iteration   1: 5.699 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   1.473 ms/op
                 createUser·p0.50:   5.333 ms/op
                 createUser·p0.90:   7.029 ms/op
                 createUser·p0.95:   8.348 ms/op
                 createUser·p0.99:   10.748 ms/op
                 createUser·p0.999:  23.997 ms/op
                 createUser·p0.9999: 33.751 ms/op
                 createUser·p1.00:   35.258 ms/op

Iteration   2: 5.535 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.630 ms/op
                 createUser·p0.50:   5.210 ms/op
                 createUser·p0.90:   6.832 ms/op
                 createUser·p0.95:   7.987 ms/op
                 createUser·p0.99:   10.043 ms/op
                 createUser·p0.999:  26.777 ms/op
                 createUser·p0.9999: 29.964 ms/op
                 createUser·p1.00:   30.704 ms/op

Iteration   3: 5.634 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.642 ms/op
                 createUser·p0.50:   5.292 ms/op
                 createUser·p0.90:   6.906 ms/op
                 createUser·p0.95:   7.873 ms/op
                 createUser·p0.99:   10.371 ms/op
                 createUser·p0.999:  28.656 ms/op
                 createUser·p0.9999: 36.045 ms/op
                 createUser·p1.00:   36.569 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 170763
  mean =      5.622 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 49222 
    [ 5.000,  7.500) = 109960 
    [ 7.500, 10.000) = 9494 
    [10.000, 12.500) = 1362 
    [12.500, 15.000) = 345 
    [15.000, 17.500) = 122 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 39 
    [27.500, 30.000) = 56 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 37 
    [35.000, 37.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.473 ms/op
     p(50.0000) =      5.276 ms/op
     p(90.0000) =      6.922 ms/op
     p(95.0000) =      8.077 ms/op
     p(99.0000) =     10.502 ms/op
     p(99.9000) =     24.805 ms/op
     p(99.9900) =     34.341 ms/op
     p(99.9990) =     36.569 ms/op
     p(99.9999) =     36.569 ms/op
    p(100.0000) =     36.569 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 20.759 ±(99.9%) 0.368 ms/op
# Warmup Iteration   2: 7.064 ±(99.9%) 0.044 ms/op
# Warmup Iteration   3: 5.484 ±(99.9%) 0.018 ms/op
Iteration   1: 5.730 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.867 ms/op
                 existUser·p0.50:   5.341 ms/op
                 existUser·p0.90:   7.283 ms/op
                 existUser·p0.95:   8.258 ms/op
                 existUser·p0.99:   11.074 ms/op
                 existUser·p0.999:  14.847 ms/op
                 existUser·p0.9999: 26.461 ms/op
                 existUser·p1.00:   26.968 ms/op

Iteration   2: 5.448 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   2.515 ms/op
                 existUser·p0.50:   5.104 ms/op
                 existUser·p0.90:   6.685 ms/op
                 existUser·p0.95:   7.602 ms/op
                 existUser·p0.99:   11.715 ms/op
                 existUser·p0.999:  26.225 ms/op
                 existUser·p0.9999: 29.139 ms/op
                 existUser·p1.00:   30.474 ms/op

Iteration   3: 5.476 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.523 ms/op
                 existUser·p0.50:   5.210 ms/op
                 existUser·p0.90:   6.447 ms/op
                 existUser·p0.95:   7.250 ms/op
                 existUser·p0.99:   10.716 ms/op
                 existUser·p0.999:  25.009 ms/op
                 existUser·p0.9999: 29.458 ms/op
                 existUser·p1.00:   30.441 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 172879
  mean =      5.549 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 61829 
    [ 5.000,  7.500) = 100631 
    [ 7.500, 10.000) = 7476 
    [10.000, 12.500) = 1963 
    [12.500, 15.000) = 591 
    [15.000, 17.500) = 162 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 86 
    [27.500, 30.000) = 55 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.515 ms/op
     p(50.0000) =      5.202 ms/op
     p(90.0000) =      6.832 ms/op
     p(95.0000) =      7.766 ms/op
     p(99.0000) =     11.207 ms/op
     p(99.9000) =     23.379 ms/op
     p(99.9900) =     29.131 ms/op
     p(99.9990) =     30.450 ms/op
     p(99.9999) =     30.474 ms/op
    p(100.0000) =     30.474 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 20.530 ±(99.9%) 0.327 ms/op
# Warmup Iteration   2: 8.233 ±(99.9%) 0.070 ms/op
# Warmup Iteration   3: 5.859 ±(99.9%) 0.025 ms/op
Iteration   1: 5.569 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.519 ms/op
                 getUser·p0.50:   5.308 ms/op
                 getUser·p0.90:   6.488 ms/op
                 getUser·p0.95:   7.578 ms/op
                 getUser·p0.99:   10.741 ms/op
                 getUser·p0.999:  15.223 ms/op
                 getUser·p0.9999: 29.901 ms/op
                 getUser·p1.00:   30.671 ms/op

Iteration   2: 5.778 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   2.490 ms/op
                 getUser·p0.50:   5.366 ms/op
                 getUser·p0.90:   7.094 ms/op
                 getUser·p0.95:   8.585 ms/op
                 getUser·p0.99:   12.730 ms/op
                 getUser·p0.999:  26.880 ms/op
                 getUser·p0.9999: 30.906 ms/op
                 getUser·p1.00:   36.307 ms/op

Iteration   3: 5.935 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   0.509 ms/op
                 getUser·p0.50:   5.669 ms/op
                 getUser·p0.90:   7.422 ms/op
                 getUser·p0.95:   8.389 ms/op
                 getUser·p0.99:   10.519 ms/op
                 getUser·p0.999:  26.974 ms/op
                 getUser·p0.9999: 30.869 ms/op
                 getUser·p1.00:   32.571 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 166603
  mean =      5.756 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7 
    [ 2.500,  5.000) = 44792 
    [ 5.000,  7.500) = 109298 
    [ 7.500, 10.000) = 9484 
    [10.000, 12.500) = 1981 
    [12.500, 15.000) = 585 
    [15.000, 17.500) = 136 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 56 
    [25.000, 27.500) = 76 
    [27.500, 30.000) = 69 
    [30.000, 32.500) = 33 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.509 ms/op
     p(50.0000) =      5.399 ms/op
     p(90.0000) =      7.053 ms/op
     p(95.0000) =      8.282 ms/op
     p(99.0000) =     11.255 ms/op
     p(99.9000) =     25.585 ms/op
     p(99.9900) =     30.638 ms/op
     p(99.9990) =     36.132 ms/op
     p(99.9999) =     36.307 ms/op
    p(100.0000) =     36.307 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 22.979 ±(99.9%) 0.428 ms/op
# Warmup Iteration   2: 10.370 ±(99.9%) 0.101 ms/op
# Warmup Iteration   3: 6.968 ±(99.9%) 0.032 ms/op
Iteration   1: 6.797 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   2.179 ms/op
                 listUser·p0.50:   6.414 ms/op
                 listUser·p0.90:   8.086 ms/op
                 listUser·p0.95:   9.470 ms/op
                 listUser·p0.99:   13.484 ms/op
                 listUser·p0.999:  27.215 ms/op
                 listUser·p0.9999: 31.293 ms/op
                 listUser·p1.00:   31.392 ms/op

Iteration   2: 6.490 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   2.818 ms/op
                 listUser·p0.50:   6.169 ms/op
                 listUser·p0.90:   7.528 ms/op
                 listUser·p0.95:   8.765 ms/op
                 listUser·p0.99:   12.095 ms/op
                 listUser·p0.999:  27.765 ms/op
                 listUser·p0.9999: 30.961 ms/op
                 listUser·p1.00:   32.178 ms/op

Iteration   3: 6.775 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   3.625 ms/op
                 listUser·p0.50:   6.324 ms/op
                 listUser·p0.90:   8.334 ms/op
                 listUser·p0.95:   9.628 ms/op
                 listUser·p0.99:   12.935 ms/op
                 listUser·p0.999:  29.509 ms/op
                 listUser·p0.9999: 38.011 ms/op
                 listUser·p1.00:   38.076 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 143620
  mean =      6.684 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 2668 
    [ 5.000,  7.500) = 119124 
    [ 7.500, 10.000) = 16636 
    [10.000, 12.500) = 3462 
    [12.500, 15.000) = 958 
    [15.000, 17.500) = 317 
    [17.500, 20.000) = 109 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 81 
    [25.000, 27.500) = 83 
    [27.500, 30.000) = 83 
    [30.000, 32.500) = 37 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      2.179 ms/op
     p(50.0000) =      6.283 ms/op
     p(90.0000) =      8.004 ms/op
     p(95.0000) =      9.339 ms/op
     p(99.0000) =     12.960 ms/op
     p(99.9000) =     27.820 ms/op
     p(99.9900) =     36.110 ms/op
     p(99.9990) =     38.076 ms/op
     p(99.9999) =     38.076 ms/op
    p(100.0000) =     38.076 ms/op


# Run complete. Total time: 00:13:20

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.725 ± 1.536  ops/ms
ClientPb.existUser                       thrpt       3   5.826 ± 2.514  ops/ms
ClientPb.getUser                         thrpt       3   5.517 ± 3.418  ops/ms
ClientPb.listUser                        thrpt       3   4.720 ± 1.750  ops/ms
ClientPb.createUser                       avgt       3   5.786 ± 4.495   ms/op
ClientPb.existUser                        avgt       3   5.437 ± 0.912   ms/op
ClientPb.getUser                          avgt       3   5.870 ± 3.260   ms/op
ClientPb.listUser                         avgt       3   6.619 ± 0.660   ms/op
ClientPb.createUser                     sample  170763   5.622 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.473           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.276           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.922           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.077           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.502           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.805           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.341           ms/op
ClientPb.createUser:createUser·p1.00    sample          36.569           ms/op
ClientPb.existUser                      sample  172879   5.549 ± 0.012   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.515           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.202           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.832           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.766           ms/op
ClientPb.existUser:existUser·p0.99      sample          11.207           ms/op
ClientPb.existUser:existUser·p0.999     sample          23.379           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.131           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.474           ms/op
ClientPb.getUser                        sample  166603   5.756 ± 0.013   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.509           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.399           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.053           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.282           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.255           ms/op
ClientPb.getUser:getUser·p0.999         sample          25.585           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.638           ms/op
ClientPb.getUser:getUser·p1.00          sample          36.307           ms/op
ClientPb.listUser                       sample  143620   6.684 ± 0.015   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.179           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.283           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.004           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.339           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.960           ms/op
ClientPb.listUser:listUser·p0.999       sample          27.820           ms/op
ClientPb.listUser:listUser·p0.9999      sample          36.110           ms/op
ClientPb.listUser:listUser·p1.00        sample          38.076           ms/op
