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
# Warmup Iteration   1: 1.003 ops/ms
# Warmup Iteration   2: 2.465 ops/ms
# Warmup Iteration   3: 5.459 ops/ms
Iteration   1: 5.543 ops/ms
Iteration   2: 5.726 ops/ms
Iteration   3: 6.024 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.764 ±(99.9%) 4.437 ops/ms [Average]
  (min, avg, max) = (5.543, 5.764, 6.024), stdev = 0.243
  CI (99.9%): [1.327, 10.202] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 1.617 ops/ms
# Warmup Iteration   2: 5.222 ops/ms
# Warmup Iteration   3: 6.321 ops/ms
Iteration   1: 6.401 ops/ms
Iteration   2: 6.523 ops/ms
Iteration   3: 6.700 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.541 ±(99.9%) 2.741 ops/ms [Average]
  (min, avg, max) = (6.401, 6.541, 6.700), stdev = 0.150
  CI (99.9%): [3.800, 9.282] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 1.768 ops/ms
# Warmup Iteration   2: 5.404 ops/ms
# Warmup Iteration   3: 6.225 ops/ms
Iteration   1: 6.016 ops/ms
Iteration   2: 6.089 ops/ms
Iteration   3: 6.145 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.083 ±(99.9%) 1.184 ops/ms [Average]
  (min, avg, max) = (6.016, 6.083, 6.145), stdev = 0.065
  CI (99.9%): [4.899, 7.267] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 1.658 ops/ms
# Warmup Iteration   2: 4.700 ops/ms
# Warmup Iteration   3: 5.507 ops/ms
Iteration   1: 4.990 ops/ms
Iteration   2: 5.400 ops/ms
Iteration   3: 5.226 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.206 ±(99.9%) 3.755 ops/ms [Average]
  (min, avg, max) = (4.990, 5.206, 5.400), stdev = 0.206
  CI (99.9%): [1.450, 8.961] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 20.141 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 7.191 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 5.705 ±(99.9%) 0.010 ms/op
Iteration   1: 5.488 ±(99.9%) 0.010 ms/op
Iteration   2: 5.329 ±(99.9%) 0.016 ms/op
Iteration   3: 5.133 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.316 ±(99.9%) 3.246 ms/op [Average]
  (min, avg, max) = (5.133, 5.316, 5.488), stdev = 0.178
  CI (99.9%): [2.070, 8.563] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 14.783 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 5.479 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.080 ±(99.9%) 0.009 ms/op
Iteration   1: 4.769 ±(99.9%) 0.017 ms/op
Iteration   2: 4.943 ±(99.9%) 0.010 ms/op
Iteration   3: 4.967 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.893 ±(99.9%) 1.966 ms/op [Average]
  (min, avg, max) = (4.769, 4.893, 4.967), stdev = 0.108
  CI (99.9%): [2.927, 6.860] (assumes normal distribution)


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
# Warmup Iteration   1: 17.539 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 7.170 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.509 ±(99.9%) 0.012 ms/op
Iteration   1: 5.312 ±(99.9%) 0.009 ms/op
Iteration   2: 5.152 ±(99.9%) 0.009 ms/op
Iteration   3: 5.074 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.179 ±(99.9%) 2.214 ms/op [Average]
  (min, avg, max) = (5.074, 5.179, 5.312), stdev = 0.121
  CI (99.9%): [2.965, 7.393] (assumes normal distribution)


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
# Warmup Iteration   1: 20.503 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 7.829 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 6.376 ±(99.9%) 0.009 ms/op
Iteration   1: 6.320 ±(99.9%) 0.015 ms/op
Iteration   2: 6.065 ±(99.9%) 0.016 ms/op
Iteration   3: 5.944 ±(99.9%) 0.026 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.110 ±(99.9%) 3.505 ms/op [Average]
  (min, avg, max) = (5.944, 6.110, 6.320), stdev = 0.192
  CI (99.9%): [2.604, 9.615] (assumes normal distribution)


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
# Warmup Iteration   1: 16.998 ±(99.9%) 0.308 ms/op
# Warmup Iteration   2: 6.757 ±(99.9%) 0.039 ms/op
# Warmup Iteration   3: 5.511 ±(99.9%) 0.023 ms/op
Iteration   1: 4.980 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   0.850 ms/op
                 createUser·p0.50:   4.743 ms/op
                 createUser·p0.90:   5.857 ms/op
                 createUser·p0.95:   6.742 ms/op
                 createUser·p0.99:   9.011 ms/op
                 createUser·p0.999:  22.412 ms/op
                 createUser·p0.9999: 27.268 ms/op
                 createUser·p1.00:   27.525 ms/op

Iteration   2: 5.205 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   2.265 ms/op
                 createUser·p0.50:   4.932 ms/op
                 createUser·p0.90:   6.283 ms/op
                 createUser·p0.95:   6.906 ms/op
                 createUser·p0.99:   9.562 ms/op
                 createUser·p0.999:  25.067 ms/op
                 createUser·p0.9999: 27.460 ms/op
                 createUser·p1.00:   28.246 ms/op

Iteration   3: 5.127 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   2.343 ms/op
                 createUser·p0.50:   4.801 ms/op
                 createUser·p0.90:   6.316 ms/op
                 createUser·p0.95:   7.414 ms/op
                 createUser·p0.99:   8.995 ms/op
                 createUser·p0.999:  26.007 ms/op
                 createUser·p0.9999: 27.976 ms/op
                 createUser·p1.00:   28.869 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 187870
  mean =      5.102 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21 
    [ 2.500,  5.000) = 117949 
    [ 5.000,  7.500) = 62996 
    [ 7.500, 10.000) = 5820 
    [10.000, 12.500) = 617 
    [12.500, 15.000) = 177 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 151 

  Percentiles, ms/op:
      p(0.0000) =      0.850 ms/op
     p(50.0000) =      4.801 ms/op
     p(90.0000) =      6.177 ms/op
     p(95.0000) =      7.012 ms/op
     p(99.0000) =      9.191 ms/op
     p(99.9000) =     24.351 ms/op
     p(99.9900) =     27.598 ms/op
     p(99.9990) =     28.840 ms/op
     p(99.9999) =     28.869 ms/op
    p(100.0000) =     28.869 ms/op


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
# Warmup Iteration   1: 16.916 ±(99.9%) 0.255 ms/op
# Warmup Iteration   2: 5.884 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 5.232 ±(99.9%) 0.019 ms/op
Iteration   1: 5.124 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.220 ms/op
                 existUser·p0.50:   4.710 ms/op
                 existUser·p0.90:   6.496 ms/op
                 existUser·p0.95:   7.774 ms/op
                 existUser·p0.99:   10.961 ms/op
                 existUser·p0.999:  22.462 ms/op
                 existUser·p0.9999: 25.559 ms/op
                 existUser·p1.00:   25.788 ms/op

Iteration   2: 5.314 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.724 ms/op
                 existUser·p0.50:   4.899 ms/op
                 existUser·p0.90:   6.799 ms/op
                 existUser·p0.95:   7.995 ms/op
                 existUser·p0.99:   11.092 ms/op
                 existUser·p0.999:  27.947 ms/op
                 existUser·p0.9999: 34.995 ms/op
                 existUser·p1.00:   35.193 ms/op

Iteration   3: 5.124 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.804 ms/op
                 existUser·p0.50:   4.784 ms/op
                 existUser·p0.90:   6.324 ms/op
                 existUser·p0.95:   7.299 ms/op
                 existUser·p0.99:   10.273 ms/op
                 existUser·p0.999:  16.049 ms/op
                 existUser·p0.9999: 32.588 ms/op
                 existUser·p1.00:   33.030 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 185072
  mean =      5.186 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 54 
    [ 2.500,  5.000) = 111922 
    [ 5.000,  7.500) = 62473 
    [ 7.500, 10.000) = 8032 
    [10.000, 12.500) = 1699 
    [12.500, 15.000) = 541 
    [15.000, 17.500) = 146 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 13 
    [27.500, 30.000) = 11 
    [30.000, 32.500) = 44 
    [32.500, 35.000) = 37 
    [35.000, 37.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.724 ms/op
     p(50.0000) =      4.792 ms/op
     p(90.0000) =      6.537 ms/op
     p(95.0000) =      7.725 ms/op
     p(99.0000) =     10.781 ms/op
     p(99.9000) =     20.873 ms/op
     p(99.9900) =     34.406 ms/op
     p(99.9990) =     35.193 ms/op
     p(99.9999) =     35.193 ms/op
    p(100.0000) =     35.193 ms/op


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
# Warmup Iteration   1: 18.125 ±(99.9%) 0.338 ms/op
# Warmup Iteration   2: 6.246 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 5.080 ±(99.9%) 0.017 ms/op
Iteration   1: 5.336 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   1.497 ms/op
                 getUser·p0.50:   5.005 ms/op
                 getUser·p0.90:   6.472 ms/op
                 getUser·p0.95:   7.709 ms/op
                 getUser·p0.99:   10.945 ms/op
                 getUser·p0.999:  21.823 ms/op
                 getUser·p0.9999: 25.659 ms/op
                 getUser·p1.00:   26.771 ms/op

Iteration   2: 5.524 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   2.241 ms/op
                 getUser·p0.50:   5.095 ms/op
                 getUser·p0.90:   6.849 ms/op
                 getUser·p0.95:   8.651 ms/op
                 getUser·p0.99:   12.517 ms/op
                 getUser·p0.999:  25.694 ms/op
                 getUser·p0.9999: 28.901 ms/op
                 getUser·p1.00:   29.262 ms/op

Iteration   3: 5.233 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   2.114 ms/op
                 getUser·p0.50:   5.005 ms/op
                 getUser·p0.90:   6.220 ms/op
                 getUser·p0.95:   6.939 ms/op
                 getUser·p0.99:   9.683 ms/op
                 getUser·p0.999:  23.603 ms/op
                 getUser·p0.9999: 27.711 ms/op
                 getUser·p1.00:   28.770 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 178893
  mean =      5.362 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 85847 
    [ 5.000,  7.500) = 83406 
    [ 7.500, 10.000) = 6649 
    [10.000, 12.500) = 1829 
    [12.500, 15.000) = 620 
    [15.000, 17.500) = 174 
    [17.500, 20.000) = 87 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 62 
    [25.000, 27.500) = 121 

  Percentiles, ms/op:
      p(0.0000) =      1.497 ms/op
     p(50.0000) =      5.030 ms/op
     p(90.0000) =      6.480 ms/op
     p(95.0000) =      7.684 ms/op
     p(99.0000) =     11.141 ms/op
     p(99.9000) =     23.760 ms/op
     p(99.9900) =     28.515 ms/op
     p(99.9990) =     29.133 ms/op
     p(99.9999) =     29.262 ms/op
    p(100.0000) =     29.262 ms/op


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
# Warmup Iteration   1: 17.070 ±(99.9%) 0.299 ms/op
# Warmup Iteration   2: 7.180 ±(99.9%) 0.044 ms/op
# Warmup Iteration   3: 6.301 ±(99.9%) 0.023 ms/op
Iteration   1: 6.083 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.778 ms/op
                 listUser·p0.50:   5.743 ms/op
                 listUser·p0.90:   7.299 ms/op
                 listUser·p0.95:   8.315 ms/op
                 listUser·p0.99:   11.174 ms/op
                 listUser·p0.999:  27.696 ms/op
                 listUser·p0.9999: 33.546 ms/op
                 listUser·p1.00:   34.275 ms/op

Iteration   2: 6.224 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   2.626 ms/op
                 listUser·p0.50:   5.874 ms/op
                 listUser·p0.90:   7.569 ms/op
                 listUser·p0.95:   8.962 ms/op
                 listUser·p0.99:   11.731 ms/op
                 listUser·p0.999:  27.971 ms/op
                 listUser·p0.9999: 30.289 ms/op
                 listUser·p1.00:   32.047 ms/op

Iteration   3: 5.994 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   2.933 ms/op
                 listUser·p0.50:   5.718 ms/op
                 listUser·p0.90:   6.980 ms/op
                 listUser·p0.95:   7.873 ms/op
                 listUser·p0.99:   11.289 ms/op
                 listUser·p0.999:  21.246 ms/op
                 listUser·p0.9999: 23.495 ms/op
                 listUser·p1.00:   24.805 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 157304
  mean =      6.099 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 11651 
    [ 5.000,  7.500) = 132420 
    [ 7.500, 10.000) = 9750 
    [10.000, 12.500) = 2589 
    [12.500, 15.000) = 412 
    [15.000, 17.500) = 115 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 84 
    [27.500, 30.000) = 84 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 11 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.778 ms/op
     p(50.0000) =      5.775 ms/op
     p(90.0000) =      7.266 ms/op
     p(95.0000) =      8.438 ms/op
     p(99.0000) =     11.354 ms/op
     p(99.9000) =     26.608 ms/op
     p(99.9900) =     31.868 ms/op
     p(99.9990) =     34.238 ms/op
     p(99.9999) =     34.275 ms/op
    p(100.0000) =     34.275 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.764 ± 4.437  ops/ms
ClientPb.existUser                       thrpt       3   6.541 ± 2.741  ops/ms
ClientPb.getUser                         thrpt       3   6.083 ± 1.184  ops/ms
ClientPb.listUser                        thrpt       3   5.206 ± 3.755  ops/ms
ClientPb.createUser                       avgt       3   5.316 ± 3.246   ms/op
ClientPb.existUser                        avgt       3   4.893 ± 1.966   ms/op
ClientPb.getUser                          avgt       3   5.179 ± 2.214   ms/op
ClientPb.listUser                         avgt       3   6.110 ± 3.505   ms/op
ClientPb.createUser                     sample  187870   5.102 ± 0.010   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.850           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.801           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.177           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.012           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.191           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.351           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.598           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.869           ms/op
ClientPb.existUser                      sample  185072   5.186 ± 0.012   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.724           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.792           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.537           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.725           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.781           ms/op
ClientPb.existUser:existUser·p0.999     sample          20.873           ms/op
ClientPb.existUser:existUser·p0.9999    sample          34.406           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.193           ms/op
ClientPb.getUser                        sample  178893   5.362 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.497           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.030           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.480           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.684           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.141           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.760           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.515           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.262           ms/op
ClientPb.listUser                       sample  157304   6.099 ± 0.013   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.778           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.775           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.266           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.438           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.354           ms/op
ClientPb.listUser:listUser·p0.999       sample          26.608           ms/op
ClientPb.listUser:listUser·p0.9999      sample          31.868           ms/op
ClientPb.listUser:listUser·p1.00        sample          34.275           ms/op
