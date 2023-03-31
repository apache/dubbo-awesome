# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 0.830 ops/ms
# Warmup Iteration   2: 2.436 ops/ms
# Warmup Iteration   3: 5.544 ops/ms
Iteration   1: 6.372 ops/ms
Iteration   2: 5.825 ops/ms
Iteration   3: 6.163 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.120 ±(99.9%) 5.032 ops/ms [Average]
  (min, avg, max) = (5.825, 6.120, 6.372), stdev = 0.276
  CI (99.9%): [1.088, 11.152] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:13
# Fork: 1 of 1
# Warmup Iteration   1: 1.558 ops/ms
# Warmup Iteration   2: 5.213 ops/ms
# Warmup Iteration   3: 6.422 ops/ms
Iteration   1: 6.437 ops/ms
Iteration   2: 6.608 ops/ms
Iteration   3: 6.717 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.587 ±(99.9%) 2.573 ops/ms [Average]
  (min, avg, max) = (6.437, 6.587, 6.717), stdev = 0.141
  CI (99.9%): [4.015, 9.160] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:06
# Fork: 1 of 1
# Warmup Iteration   1: 1.644 ops/ms
# Warmup Iteration   2: 5.023 ops/ms
# Warmup Iteration   3: 5.996 ops/ms
Iteration   1: 5.784 ops/ms
Iteration   2: 6.080 ops/ms
Iteration   3: 6.054 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.973 ±(99.9%) 2.985 ops/ms [Average]
  (min, avg, max) = (5.784, 5.973, 6.080), stdev = 0.164
  CI (99.9%): [2.987, 8.958] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:59
# Fork: 1 of 1
# Warmup Iteration   1: 1.587 ops/ms
# Warmup Iteration   2: 3.972 ops/ms
# Warmup Iteration   3: 5.119 ops/ms
Iteration   1: 5.275 ops/ms
Iteration   2: 5.373 ops/ms
Iteration   3: 5.273 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.307 ±(99.9%) 1.047 ops/ms [Average]
  (min, avg, max) = (5.273, 5.307, 5.373), stdev = 0.057
  CI (99.9%): [4.260, 6.354] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:53
# Fork: 1 of 1
# Warmup Iteration   1: 19.993 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 6.767 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.524 ±(99.9%) 0.016 ms/op
Iteration   1: 5.108 ±(99.9%) 0.014 ms/op
Iteration   2: 5.372 ±(99.9%) 0.018 ms/op
Iteration   3: 5.060 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.180 ±(99.9%) 3.061 ms/op [Average]
  (min, avg, max) = (5.060, 5.180, 5.372), stdev = 0.168
  CI (99.9%): [2.119, 8.241] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:46
# Fork: 1 of 1
# Warmup Iteration   1: 14.846 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 6.187 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.132 ±(99.9%) 0.015 ms/op
Iteration   1: 5.007 ±(99.9%) 0.012 ms/op
Iteration   2: 4.785 ±(99.9%) 0.013 ms/op
Iteration   3: 4.874 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.889 ±(99.9%) 2.036 ms/op [Average]
  (min, avg, max) = (4.785, 4.889, 5.007), stdev = 0.112
  CI (99.9%): [2.852, 6.925] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:39
# Fork: 1 of 1
# Warmup Iteration   1: 17.614 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 5.959 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 5.649 ±(99.9%) 0.008 ms/op
Iteration   1: 5.121 ±(99.9%) 0.012 ms/op
Iteration   2: 5.161 ±(99.9%) 0.016 ms/op
Iteration   3: 5.129 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.137 ±(99.9%) 0.387 ms/op [Average]
  (min, avg, max) = (5.121, 5.137, 5.161), stdev = 0.021
  CI (99.9%): [4.750, 5.524] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 20.048 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 7.332 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 6.321 ±(99.9%) 0.013 ms/op
Iteration   1: 6.301 ±(99.9%) 0.018 ms/op
Iteration   2: 5.949 ±(99.9%) 0.015 ms/op
Iteration   3: 6.220 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.157 ±(99.9%) 3.366 ms/op [Average]
  (min, avg, max) = (5.949, 6.157, 6.301), stdev = 0.184
  CI (99.9%): [2.791, 9.522] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:26
# Fork: 1 of 1
# Warmup Iteration   1: 18.724 ±(99.9%) 0.303 ms/op
# Warmup Iteration   2: 7.158 ±(99.9%) 0.057 ms/op
# Warmup Iteration   3: 5.715 ±(99.9%) 0.030 ms/op
Iteration   1: 5.111 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   2.363 ms/op
                 createUser·p0.50:   4.833 ms/op
                 createUser·p0.90:   6.226 ms/op
                 createUser·p0.95:   7.152 ms/op
                 createUser·p0.99:   9.814 ms/op
                 createUser·p0.999:  24.262 ms/op
                 createUser·p0.9999: 31.416 ms/op
                 createUser·p1.00:   32.014 ms/op

Iteration   2: 5.426 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   2.183 ms/op
                 createUser·p0.50:   5.038 ms/op
                 createUser·p0.90:   6.791 ms/op
                 createUser·p0.95:   8.110 ms/op
                 createUser·p0.99:   11.846 ms/op
                 createUser·p0.999:  25.919 ms/op
                 createUser·p0.9999: 30.536 ms/op
                 createUser·p1.00:   31.457 ms/op

Iteration   3: 5.267 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.704 ms/op
                 createUser·p0.50:   4.997 ms/op
                 createUser·p0.90:   6.447 ms/op
                 createUser·p0.95:   7.283 ms/op
                 createUser·p0.99:   9.798 ms/op
                 createUser·p0.999:  27.730 ms/op
                 createUser·p0.9999: 32.441 ms/op
                 createUser·p1.00:   32.965 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 182327
  mean =      5.265 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28 
    [ 2.500,  5.000) = 96813 
    [ 5.000,  7.500) = 76060 
    [ 7.500, 10.000) = 7066 
    [10.000, 12.500) = 1673 
    [12.500, 15.000) = 367 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 50 
    [27.500, 30.000) = 74 
    [30.000, 32.500) = 48 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.704 ms/op
     p(50.0000) =      4.940 ms/op
     p(90.0000) =      6.472 ms/op
     p(95.0000) =      7.569 ms/op
     p(99.0000) =     10.617 ms/op
     p(99.9000) =     24.707 ms/op
     p(99.9900) =     31.450 ms/op
     p(99.9990) =     32.722 ms/op
     p(99.9999) =     32.965 ms/op
    p(100.0000) =     32.965 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 17.043 ±(99.9%) 0.277 ms/op
# Warmup Iteration   2: 5.428 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 5.005 ±(99.9%) 0.018 ms/op
Iteration   1: 4.775 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.138 ms/op
                 existUser·p0.50:   4.489 ms/op
                 existUser·p0.90:   5.751 ms/op
                 existUser·p0.95:   6.717 ms/op
                 existUser·p0.99:   10.142 ms/op
                 existUser·p0.999:  17.727 ms/op
                 existUser·p0.9999: 25.625 ms/op
                 existUser·p1.00:   26.345 ms/op

Iteration   2: 4.853 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   1.360 ms/op
                 existUser·p0.50:   4.489 ms/op
                 existUser·p0.90:   6.267 ms/op
                 existUser·p0.95:   7.389 ms/op
                 existUser·p0.99:   10.338 ms/op
                 existUser·p0.999:  15.385 ms/op
                 existUser·p0.9999: 36.335 ms/op
                 existUser·p1.00:   42.271 ms/op

Iteration   3: 5.008 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.294 ms/op
                 existUser·p0.50:   4.620 ms/op
                 existUser·p0.90:   6.210 ms/op
                 existUser·p0.95:   7.700 ms/op
                 existUser·p0.99:   11.026 ms/op
                 existUser·p0.999:  28.367 ms/op
                 existUser·p0.9999: 33.751 ms/op
                 existUser·p1.00:   34.013 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 196841
  mean =      4.877 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 143699 
    [ 5.000, 10.000) = 50687 
    [10.000, 15.000) = 2165 
    [15.000, 20.000) = 122 
    [20.000, 25.000) = 56 
    [25.000, 30.000) = 29 
    [30.000, 35.000) = 65 
    [35.000, 40.000) = 15 
    [40.000, 45.000) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.360 ms/op
     p(50.0000) =      4.538 ms/op
     p(90.0000) =      6.070 ms/op
     p(95.0000) =      7.266 ms/op
     p(99.0000) =     10.502 ms/op
     p(99.9000) =     16.321 ms/op
     p(99.9900) =     34.951 ms/op
     p(99.9990) =     41.446 ms/op
     p(99.9999) =     42.271 ms/op
    p(100.0000) =     42.271 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 18.177 ±(99.9%) 0.288 ms/op
# Warmup Iteration   2: 6.190 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 5.203 ±(99.9%) 0.019 ms/op
Iteration   1: 5.229 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.535 ms/op
                 getUser·p0.50:   4.899 ms/op
                 getUser·p0.90:   6.373 ms/op
                 getUser·p0.95:   7.512 ms/op
                 getUser·p0.99:   10.764 ms/op
                 getUser·p0.999:  22.540 ms/op
                 getUser·p0.9999: 27.579 ms/op
                 getUser·p1.00:   28.115 ms/op

Iteration   2: 5.233 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   1.827 ms/op
                 getUser·p0.50:   4.743 ms/op
                 getUser·p0.90:   7.086 ms/op
                 getUser·p0.95:   8.184 ms/op
                 getUser·p0.99:   11.223 ms/op
                 getUser·p0.999:  25.162 ms/op
                 getUser·p0.9999: 29.488 ms/op
                 getUser·p1.00:   29.884 ms/op

Iteration   3: 5.075 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.815 ms/op
                 getUser·p0.50:   4.817 ms/op
                 getUser·p0.90:   6.185 ms/op
                 getUser·p0.95:   6.889 ms/op
                 getUser·p0.99:   9.522 ms/op
                 getUser·p0.999:  25.324 ms/op
                 getUser·p0.9999: 29.755 ms/op
                 getUser·p1.00:   31.195 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 185331
  mean =      5.178 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27 
    [ 2.500,  5.000) = 110859 
    [ 5.000,  7.500) = 64553 
    [ 7.500, 10.000) = 7424 
    [10.000, 12.500) = 1609 
    [12.500, 15.000) = 450 
    [15.000, 17.500) = 182 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 122 
    [27.500, 30.000) = 35 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.815 ms/op
     p(50.0000) =      4.817 ms/op
     p(90.0000) =      6.472 ms/op
     p(95.0000) =      7.602 ms/op
     p(99.0000) =     10.628 ms/op
     p(99.9000) =     22.796 ms/op
     p(99.9900) =     29.129 ms/op
     p(99.9990) =     31.055 ms/op
     p(99.9999) =     31.195 ms/op
    p(100.0000) =     31.195 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 18.580 ±(99.9%) 0.284 ms/op
# Warmup Iteration   2: 7.166 ±(99.9%) 0.047 ms/op
# Warmup Iteration   3: 6.156 ±(99.9%) 0.027 ms/op
Iteration   1: 6.021 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   2.822 ms/op
                 listUser·p0.50:   5.669 ms/op
                 listUser·p0.90:   7.152 ms/op
                 listUser·p0.95:   8.831 ms/op
                 listUser·p0.99:   11.960 ms/op
                 listUser·p0.999:  26.754 ms/op
                 listUser·p0.9999: 32.125 ms/op
                 listUser·p1.00:   35.389 ms/op

Iteration   2: 5.801 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   2.888 ms/op
                 listUser·p0.50:   5.448 ms/op
                 listUser·p0.90:   7.053 ms/op
                 listUser·p0.95:   8.143 ms/op
                 listUser·p0.99:   10.994 ms/op
                 listUser·p0.999:  27.275 ms/op
                 listUser·p0.9999: 30.751 ms/op
                 listUser·p1.00:   31.556 ms/op

Iteration   3: 6.040 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   2.183 ms/op
                 listUser·p0.50:   5.685 ms/op
                 listUser·p0.90:   7.381 ms/op
                 listUser·p0.95:   8.700 ms/op
                 listUser·p0.99:   11.731 ms/op
                 listUser·p0.999:  25.824 ms/op
                 listUser·p0.9999: 36.045 ms/op
                 listUser·p1.00:   36.372 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 161185
  mean =      5.952 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 21573 
    [ 5.000,  7.500) = 126102 
    [ 7.500, 10.000) = 10010 
    [10.000, 12.500) = 2341 
    [12.500, 15.000) = 639 
    [15.000, 17.500) = 159 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 99 
    [27.500, 30.000) = 50 
    [30.000, 32.500) = 38 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      2.183 ms/op
     p(50.0000) =      5.595 ms/op
     p(90.0000) =      7.193 ms/op
     p(95.0000) =      8.569 ms/op
     p(99.0000) =     11.616 ms/op
     p(99.9000) =     26.595 ms/op
     p(99.9900) =     35.389 ms/op
     p(99.9990) =     36.252 ms/op
     p(99.9999) =     36.372 ms/op
    p(100.0000) =     36.372 ms/op


# Run complete. Total time: 00:13:19

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.120 ± 5.032  ops/ms
ClientPb.existUser                       thrpt       3   6.587 ± 2.573  ops/ms
ClientPb.getUser                         thrpt       3   5.973 ± 2.985  ops/ms
ClientPb.listUser                        thrpt       3   5.307 ± 1.047  ops/ms
ClientPb.createUser                       avgt       3   5.180 ± 3.061   ms/op
ClientPb.existUser                        avgt       3   4.889 ± 2.036   ms/op
ClientPb.getUser                          avgt       3   5.137 ± 0.387   ms/op
ClientPb.listUser                         avgt       3   6.157 ± 3.366   ms/op
ClientPb.createUser                     sample  182327   5.265 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.704           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.940           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.472           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.569           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.617           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.707           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.450           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.965           ms/op
ClientPb.existUser                      sample  196841   4.877 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.360           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.538           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.070           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.266           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.502           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.321           ms/op
ClientPb.existUser:existUser·p0.9999    sample          34.951           ms/op
ClientPb.existUser:existUser·p1.00      sample          42.271           ms/op
ClientPb.getUser                        sample  185331   5.178 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.815           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.817           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.472           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.602           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.628           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.796           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.129           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.195           ms/op
ClientPb.listUser                       sample  161185   5.952 ± 0.013   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.183           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.595           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.193           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.569           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.616           ms/op
ClientPb.listUser:listUser·p0.999       sample          26.595           ms/op
ClientPb.listUser:listUser·p0.9999      sample          35.389           ms/op
ClientPb.listUser:listUser·p1.00        sample          36.372           ms/op
