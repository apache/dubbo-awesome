# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.617 ops/ms
# Warmup Iteration   2: 3.556 ops/ms
# Warmup Iteration   3: 6.468 ops/ms
Iteration   1: 7.170 ops/ms
Iteration   2: 7.478 ops/ms
Iteration   3: 6.942 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.197 ±(99.9%) 4.905 ops/ms [Average]
  (min, avg, max) = (6.942, 7.197, 7.478), stdev = 0.269
  CI (99.9%): [2.292, 12.102] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 1.987 ops/ms
# Warmup Iteration   2: 5.854 ops/ms
# Warmup Iteration   3: 7.504 ops/ms
Iteration   1: 7.392 ops/ms
Iteration   2: 7.786 ops/ms
Iteration   3: 7.706 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  7.628 ±(99.9%) 3.801 ops/ms [Average]
  (min, avg, max) = (7.392, 7.628, 7.786), stdev = 0.208
  CI (99.9%): [3.826, 11.429] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 1.871 ops/ms
# Warmup Iteration   2: 5.767 ops/ms
# Warmup Iteration   3: 7.109 ops/ms
Iteration   1: 7.178 ops/ms
Iteration   2: 7.173 ops/ms
Iteration   3: 7.487 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.279 ±(99.9%) 3.275 ops/ms [Average]
  (min, avg, max) = (7.173, 7.279, 7.487), stdev = 0.179
  CI (99.9%): [4.005, 10.554] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 1.787 ops/ms
# Warmup Iteration   2: 4.821 ops/ms
# Warmup Iteration   3: 6.010 ops/ms
Iteration   1: 5.985 ops/ms
Iteration   2: 6.393 ops/ms
Iteration   3: 6.204 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.194 ±(99.9%) 3.730 ops/ms [Average]
  (min, avg, max) = (5.985, 6.194, 6.393), stdev = 0.204
  CI (99.9%): [2.464, 9.924] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 14.312 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 5.284 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.459 ±(99.9%) 0.006 ms/op
Iteration   1: 4.289 ±(99.9%) 0.006 ms/op
Iteration   2: 4.229 ±(99.9%) 0.007 ms/op
Iteration   3: 4.315 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.278 ±(99.9%) 0.808 ms/op [Average]
  (min, avg, max) = (4.229, 4.278, 4.315), stdev = 0.044
  CI (99.9%): [3.470, 5.086] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 13.314 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.623 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.248 ±(99.9%) 0.006 ms/op
Iteration   1: 4.331 ±(99.9%) 0.006 ms/op
Iteration   2: 4.101 ±(99.9%) 0.006 ms/op
Iteration   3: 4.220 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.217 ±(99.9%) 2.097 ms/op [Average]
  (min, avg, max) = (4.101, 4.217, 4.331), stdev = 0.115
  CI (99.9%): [2.120, 6.315] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 13.250 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 5.831 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.325 ±(99.9%) 0.008 ms/op
Iteration   1: 4.328 ±(99.9%) 0.008 ms/op
Iteration   2: 4.297 ±(99.9%) 0.007 ms/op
Iteration   3: 4.223 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.283 ±(99.9%) 0.990 ms/op [Average]
  (min, avg, max) = (4.223, 4.283, 4.328), stdev = 0.054
  CI (99.9%): [3.292, 5.273] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 16.784 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 6.129 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.380 ±(99.9%) 0.007 ms/op
Iteration   1: 5.219 ±(99.9%) 0.009 ms/op
Iteration   2: 4.935 ±(99.9%) 0.009 ms/op
Iteration   3: 5.255 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.136 ±(99.9%) 3.194 ms/op [Average]
  (min, avg, max) = (4.935, 5.136, 5.255), stdev = 0.175
  CI (99.9%): [1.942, 8.330] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 14.832 ±(99.9%) 0.217 ms/op
# Warmup Iteration   2: 6.443 ±(99.9%) 0.048 ms/op
# Warmup Iteration   3: 4.859 ±(99.9%) 0.025 ms/op
Iteration   1: 4.517 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.651 ms/op
                 createUser·p0.50:   4.145 ms/op
                 createUser·p0.90:   5.743 ms/op
                 createUser·p0.95:   6.889 ms/op
                 createUser·p0.99:   9.978 ms/op
                 createUser·p0.999:  23.495 ms/op
                 createUser·p0.9999: 28.763 ms/op
                 createUser·p1.00:   29.360 ms/op

Iteration   2: 4.265 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   2.040 ms/op
                 createUser·p0.50:   3.994 ms/op
                 createUser·p0.90:   4.964 ms/op
                 createUser·p0.95:   5.792 ms/op
                 createUser·p0.99:   9.266 ms/op
                 createUser·p0.999:  23.988 ms/op
                 createUser·p0.9999: 28.083 ms/op
                 createUser·p1.00:   28.574 ms/op

Iteration   3: 4.349 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.042 ms/op
                 createUser·p0.50:   4.059 ms/op
                 createUser·p0.90:   5.349 ms/op
                 createUser·p0.95:   6.013 ms/op
                 createUser·p0.99:   8.995 ms/op
                 createUser·p0.999:  29.930 ms/op
                 createUser·p0.9999: 42.116 ms/op
                 createUser·p1.00:   42.598 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 219322
  mean =      4.374 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 191370 
    [ 5.000, 10.000) = 26262 
    [10.000, 15.000) = 1187 
    [15.000, 20.000) = 193 
    [20.000, 25.000) = 82 
    [25.000, 30.000) = 157 
    [30.000, 35.000) = 41 
    [35.000, 40.000) = 15 
    [40.000, 45.000) = 15 

  Percentiles, ms/op:
      p(0.0000) =      1.651 ms/op
     p(50.0000) =      4.067 ms/op
     p(90.0000) =      5.317 ms/op
     p(95.0000) =      6.308 ms/op
     p(99.0000) =      9.486 ms/op
     p(99.9000) =     25.264 ms/op
     p(99.9900) =     39.649 ms/op
     p(99.9990) =     42.586 ms/op
     p(99.9999) =     42.598 ms/op
    p(100.0000) =     42.598 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 12.591 ±(99.9%) 0.168 ms/op
# Warmup Iteration   2: 4.604 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.418 ±(99.9%) 0.022 ms/op
Iteration   1: 4.141 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.315 ms/op
                 existUser·p0.50:   3.883 ms/op
                 existUser·p0.90:   5.022 ms/op
                 existUser·p0.95:   6.234 ms/op
                 existUser·p0.99:   8.102 ms/op
                 existUser·p0.999:  14.310 ms/op
                 existUser·p0.9999: 26.513 ms/op
                 existUser·p1.00:   27.951 ms/op

Iteration   2: 4.179 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   1.839 ms/op
                 existUser·p0.50:   3.949 ms/op
                 existUser·p0.90:   4.809 ms/op
                 existUser·p0.95:   6.144 ms/op
                 existUser·p0.99:   8.782 ms/op
                 existUser·p0.999:  25.214 ms/op
                 existUser·p0.9999: 55.149 ms/op
                 existUser·p1.00:   59.572 ms/op

Iteration   3: 4.191 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   1.782 ms/op
                 existUser·p0.50:   3.879 ms/op
                 existUser·p0.90:   4.989 ms/op
                 existUser·p0.95:   6.360 ms/op
                 existUser·p0.99:   8.880 ms/op
                 existUser·p0.999:  31.035 ms/op
                 existUser·p0.9999: 37.555 ms/op
                 existUser·p1.00:   46.399 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 230043
  mean =      4.170 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 208077 
    [ 5.000, 10.000) = 20700 
    [10.000, 15.000) = 830 
    [15.000, 20.000) = 176 
    [20.000, 25.000) = 38 
    [25.000, 30.000) = 98 
    [30.000, 35.000) = 50 
    [35.000, 40.000) = 37 
    [40.000, 45.000) = 2 
    [45.000, 50.000) = 25 
    [50.000, 55.000) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.315 ms/op
     p(50.0000) =      3.912 ms/op
     p(90.0000) =      4.940 ms/op
     p(95.0000) =      6.259 ms/op
     p(99.0000) =      8.585 ms/op
     p(99.9000) =     24.770 ms/op
     p(99.9900) =     47.447 ms/op
     p(99.9990) =     59.225 ms/op
     p(99.9999) =     59.572 ms/op
    p(100.0000) =     59.572 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 13.856 ±(99.9%) 0.189 ms/op
# Warmup Iteration   2: 4.994 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.780 ±(99.9%) 0.020 ms/op
Iteration   1: 4.575 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   1.456 ms/op
                 getUser·p0.50:   4.104 ms/op
                 getUser·p0.90:   6.316 ms/op
                 getUser·p0.95:   7.553 ms/op
                 getUser·p0.99:   10.633 ms/op
                 getUser·p0.999:  17.236 ms/op
                 getUser·p0.9999: 34.997 ms/op
                 getUser·p1.00:   35.389 ms/op

Iteration   2: 4.452 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.511 ms/op
                 getUser·p0.50:   4.092 ms/op
                 getUser·p0.90:   5.833 ms/op
                 getUser·p0.95:   6.922 ms/op
                 getUser·p0.99:   9.044 ms/op
                 getUser·p0.999:  20.218 ms/op
                 getUser·p0.9999: 29.937 ms/op
                 getUser·p1.00:   31.261 ms/op

Iteration   3: 4.338 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   1.972 ms/op
                 getUser·p0.50:   4.063 ms/op
                 getUser·p0.90:   5.186 ms/op
                 getUser·p0.95:   6.369 ms/op
                 getUser·p0.99:   9.421 ms/op
                 getUser·p0.999:  29.065 ms/op
                 getUser·p0.9999: 33.199 ms/op
                 getUser·p1.00:   33.948 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 215545
  mean =      4.453 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 132 
    [ 2.500,  5.000) = 181947 
    [ 5.000,  7.500) = 25561 
    [ 7.500, 10.000) = 5803 
    [10.000, 12.500) = 1494 
    [12.500, 15.000) = 298 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 40 
    [27.500, 30.000) = 109 
    [30.000, 32.500) = 50 
    [32.500, 35.000) = 19 
    [35.000, 37.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.456 ms/op
     p(50.0000) =      4.084 ms/op
     p(90.0000) =      5.775 ms/op
     p(95.0000) =      6.971 ms/op
     p(99.0000) =      9.880 ms/op
     p(99.9000) =     26.542 ms/op
     p(99.9900) =     33.169 ms/op
     p(99.9990) =     35.183 ms/op
     p(99.9999) =     35.389 ms/op
    p(100.0000) =     35.389 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 15.821 ±(99.9%) 0.255 ms/op
# Warmup Iteration   2: 6.314 ±(99.9%) 0.040 ms/op
# Warmup Iteration   3: 5.686 ±(99.9%) 0.029 ms/op
Iteration   1: 5.278 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.987 ms/op
                 listUser·p0.50:   4.858 ms/op
                 listUser·p0.90:   6.316 ms/op
                 listUser·p0.95:   8.167 ms/op
                 listUser·p0.99:   12.632 ms/op
                 listUser·p0.999:  24.871 ms/op
                 listUser·p0.9999: 30.299 ms/op
                 listUser·p1.00:   30.507 ms/op

Iteration   2: 5.246 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   2.200 ms/op
                 listUser·p0.50:   4.891 ms/op
                 listUser·p0.90:   6.193 ms/op
                 listUser·p0.95:   7.930 ms/op
                 listUser·p0.99:   11.387 ms/op
                 listUser·p0.999:  24.214 ms/op
                 listUser·p0.9999: 27.227 ms/op
                 listUser·p1.00:   28.639 ms/op

Iteration   3: 5.111 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   2.093 ms/op
                 listUser·p0.50:   4.784 ms/op
                 listUser·p0.90:   5.833 ms/op
                 listUser·p0.95:   7.545 ms/op
                 listUser·p0.99:   11.207 ms/op
                 listUser·p0.999:  19.037 ms/op
                 listUser·p0.9999: 22.380 ms/op
                 listUser·p1.00:   25.264 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 184130
  mean =      5.211 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23 
    [ 2.500,  5.000) = 117039 
    [ 5.000,  7.500) = 56023 
    [ 7.500, 10.000) = 7332 
    [10.000, 12.500) = 2282 
    [12.500, 15.000) = 636 
    [15.000, 17.500) = 320 
    [17.500, 20.000) = 147 
    [20.000, 22.500) = 80 
    [22.500, 25.000) = 139 
    [25.000, 27.500) = 70 
    [27.500, 30.000) = 29 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.987 ms/op
     p(50.0000) =      4.841 ms/op
     p(90.0000) =      6.128 ms/op
     p(95.0000) =      7.938 ms/op
     p(99.0000) =     11.682 ms/op
     p(99.9000) =     23.462 ms/op
     p(99.9900) =     29.052 ms/op
     p(99.9990) =     30.479 ms/op
     p(99.9999) =     30.507 ms/op
    p(100.0000) =     30.507 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.197 ± 4.905  ops/ms
ClientPb.existUser                       thrpt       3   7.628 ± 3.801  ops/ms
ClientPb.getUser                         thrpt       3   7.279 ± 3.275  ops/ms
ClientPb.listUser                        thrpt       3   6.194 ± 3.730  ops/ms
ClientPb.createUser                       avgt       3   4.278 ± 0.808   ms/op
ClientPb.existUser                        avgt       3   4.217 ± 2.097   ms/op
ClientPb.getUser                          avgt       3   4.283 ± 0.990   ms/op
ClientPb.listUser                         avgt       3   5.136 ± 3.194   ms/op
ClientPb.createUser                     sample  219322   4.374 ± 0.010   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.651           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.067           ms/op
ClientPb.createUser:createUser·p0.90    sample           5.317           ms/op
ClientPb.createUser:createUser·p0.95    sample           6.308           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.486           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.264           ms/op
ClientPb.createUser:createUser·p0.9999  sample          39.649           ms/op
ClientPb.createUser:createUser·p1.00    sample          42.598           ms/op
ClientPb.existUser                      sample  230043   4.170 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.315           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.912           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.940           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.259           ms/op
ClientPb.existUser:existUser·p0.99      sample           8.585           ms/op
ClientPb.existUser:existUser·p0.999     sample          24.770           ms/op
ClientPb.existUser:existUser·p0.9999    sample          47.447           ms/op
ClientPb.existUser:existUser·p1.00      sample          59.572           ms/op
ClientPb.getUser                        sample  215545   4.453 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.456           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.084           ms/op
ClientPb.getUser:getUser·p0.90          sample           5.775           ms/op
ClientPb.getUser:getUser·p0.95          sample           6.971           ms/op
ClientPb.getUser:getUser·p0.99          sample           9.880           ms/op
ClientPb.getUser:getUser·p0.999         sample          26.542           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.169           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.389           ms/op
ClientPb.listUser                       sample  184130   5.211 ± 0.012   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.987           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.841           ms/op
ClientPb.listUser:listUser·p0.90        sample           6.128           ms/op
ClientPb.listUser:listUser·p0.95        sample           7.938           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.682           ms/op
ClientPb.listUser:listUser·p0.999       sample          23.462           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.052           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.507           ms/op
