# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.425 ops/ms
# Warmup Iteration   2: 6.055 ops/ms
# Warmup Iteration   3: 9.004 ops/ms
Iteration   1: 9.772 ops/ms
Iteration   2: 10.730 ops/ms
Iteration   3: 8.338 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.613 ±(99.9%) 21.965 ops/ms [Average]
  (min, avg, max) = (8.338, 9.613, 10.730), stdev = 1.204
  CI (99.9%): [≈ 0, 31.578] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.043 ops/ms
# Warmup Iteration   2: 10.383 ops/ms
# Warmup Iteration   3: 10.437 ops/ms
Iteration   1: 11.023 ops/ms
Iteration   2: 10.859 ops/ms
Iteration   3: 10.671 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.851 ±(99.9%) 3.215 ops/ms [Average]
  (min, avg, max) = (10.671, 10.851, 11.023), stdev = 0.176
  CI (99.9%): [7.636, 14.066] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.244 ops/ms
# Warmup Iteration   2: 9.278 ops/ms
# Warmup Iteration   3: 9.487 ops/ms
Iteration   1: 10.089 ops/ms
Iteration   2: 10.434 ops/ms
Iteration   3: 10.001 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.175 ±(99.9%) 4.180 ops/ms [Average]
  (min, avg, max) = (10.001, 10.175, 10.434), stdev = 0.229
  CI (99.9%): [5.995, 14.355] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.072 ops/ms
# Warmup Iteration   2: 7.935 ops/ms
# Warmup Iteration   3: 7.964 ops/ms
Iteration   1: 8.118 ops/ms
Iteration   2: 8.040 ops/ms
Iteration   3: 8.269 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.142 ±(99.9%) 2.124 ops/ms [Average]
  (min, avg, max) = (8.040, 8.142, 8.269), stdev = 0.116
  CI (99.9%): [6.018, 10.266] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 8.269 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.461 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.298 ±(99.9%) 0.006 ms/op
Iteration   1: 3.214 ±(99.9%) 0.007 ms/op
Iteration   2: 2.923 ±(99.9%) 0.012 ms/op
Iteration   3: 2.945 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.027 ±(99.9%) 2.958 ms/op [Average]
  (min, avg, max) = (2.923, 3.027, 3.214), stdev = 0.162
  CI (99.9%): [0.069, 5.985] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 6.798 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.314 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.173 ±(99.9%) 0.003 ms/op
Iteration   1: 3.188 ±(99.9%) 0.004 ms/op
Iteration   2: 3.246 ±(99.9%) 0.009 ms/op
Iteration   3: 3.152 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.196 ±(99.9%) 0.868 ms/op [Average]
  (min, avg, max) = (3.152, 3.196, 3.246), stdev = 0.048
  CI (99.9%): [2.328, 4.063] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 7.511 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.537 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.221 ±(99.9%) 0.006 ms/op
Iteration   1: 3.223 ±(99.9%) 0.008 ms/op
Iteration   2: 3.269 ±(99.9%) 0.013 ms/op
Iteration   3: 3.052 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.182 ±(99.9%) 2.083 ms/op [Average]
  (min, avg, max) = (3.052, 3.182, 3.269), stdev = 0.114
  CI (99.9%): [1.099, 5.264] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 7.416 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.148 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.984 ±(99.9%) 0.006 ms/op
Iteration   1: 3.953 ±(99.9%) 0.006 ms/op
Iteration   2: 3.560 ±(99.9%) 0.009 ms/op
Iteration   3: 3.469 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.661 ±(99.9%) 4.702 ms/op [Average]
  (min, avg, max) = (3.469, 3.661, 3.953), stdev = 0.258
  CI (99.9%): [≈ 0, 8.363] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 7.579 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 3.736 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.149 ±(99.9%) 0.009 ms/op
Iteration   1: 3.064 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.233 ms/op
                 createUser·p0.50:   2.929 ms/op
                 createUser·p0.90:   3.486 ms/op
                 createUser·p0.95:   3.777 ms/op
                 createUser·p0.99:   5.153 ms/op
                 createUser·p0.999:  9.432 ms/op
                 createUser·p0.9999: 22.479 ms/op
                 createUser·p1.00:   23.036 ms/op

Iteration   2: 3.152 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.499 ms/op
                 createUser·p0.50:   3.047 ms/op
                 createUser·p0.90:   3.600 ms/op
                 createUser·p0.95:   3.863 ms/op
                 createUser·p0.99:   5.145 ms/op
                 createUser·p0.999:  13.301 ms/op
                 createUser·p0.9999: 29.093 ms/op
                 createUser·p1.00:   29.819 ms/op

Iteration   3: 3.343 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.335 ms/op
                 createUser·p0.50:   3.269 ms/op
                 createUser·p0.90:   3.760 ms/op
                 createUser·p0.95:   4.152 ms/op
                 createUser·p0.99:   5.833 ms/op
                 createUser·p0.999:  19.137 ms/op
                 createUser·p0.9999: 26.734 ms/op
                 createUser·p1.00:   29.164 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 301468
  mean =      3.182 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11708 
    [ 2.500,  5.000) = 285005 
    [ 5.000,  7.500) = 3920 
    [ 7.500, 10.000) = 411 
    [10.000, 12.500) = 83 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 152 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 49 

  Percentiles, ms/op:
      p(0.0000) =      1.233 ms/op
     p(50.0000) =      3.088 ms/op
     p(90.0000) =      3.621 ms/op
     p(95.0000) =      3.928 ms/op
     p(99.0000) =      5.382 ms/op
     p(99.9000) =     18.907 ms/op
     p(99.9900) =     27.160 ms/op
     p(99.9990) =     29.556 ms/op
     p(99.9999) =     29.819 ms/op
    p(100.0000) =     29.819 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 6.796 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 3.469 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 2.906 ±(99.9%) 0.007 ms/op
Iteration   1: 2.946 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.049 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.289 ms/op
                 existUser·p0.95:   3.564 ms/op
                 existUser·p0.99:   4.940 ms/op
                 existUser·p0.999:  12.512 ms/op
                 existUser·p0.9999: 22.287 ms/op
                 existUser·p1.00:   23.495 ms/op

Iteration   2: 3.081 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.214 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.588 ms/op
                 existUser·p0.95:   3.924 ms/op
                 existUser·p0.99:   4.956 ms/op
                 existUser·p0.999:  12.550 ms/op
                 existUser·p0.9999: 23.777 ms/op
                 existUser·p1.00:   24.248 ms/op

Iteration   3: 3.122 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.255 ms/op
                 existUser·p0.50:   3.006 ms/op
                 existUser·p0.90:   3.527 ms/op
                 existUser·p0.95:   3.981 ms/op
                 existUser·p0.99:   5.736 ms/op
                 existUser·p0.999:  9.929 ms/op
                 existUser·p0.9999: 21.127 ms/op
                 existUser·p1.00:   22.610 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 314906
  mean =      3.048 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20582 
    [ 2.500,  5.000) = 290303 
    [ 5.000,  7.500) = 3227 
    [ 7.500, 10.000) = 349 
    [10.000, 12.500) = 168 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 98 
    [22.500, 25.000) = 63 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.049 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      3.473 ms/op
     p(95.0000) =      3.838 ms/op
     p(99.0000) =      5.194 ms/op
     p(99.9000) =     11.856 ms/op
     p(99.9900) =     23.151 ms/op
     p(99.9990) =     24.183 ms/op
     p(99.9999) =     24.248 ms/op
    p(100.0000) =     24.248 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 7.585 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 3.532 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.287 ±(99.9%) 0.011 ms/op
Iteration   1: 3.164 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.300 ms/op
                 getUser·p0.50:   2.970 ms/op
                 getUser·p0.90:   3.846 ms/op
                 getUser·p0.95:   4.571 ms/op
                 getUser·p0.99:   5.874 ms/op
                 getUser·p0.999:  9.290 ms/op
                 getUser·p0.9999: 22.180 ms/op
                 getUser·p1.00:   23.003 ms/op

Iteration   2: 2.982 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.161 ms/op
                 getUser·p0.50:   2.896 ms/op
                 getUser·p0.90:   3.346 ms/op
                 getUser·p0.95:   3.625 ms/op
                 getUser·p0.99:   5.169 ms/op
                 getUser·p0.999:  9.268 ms/op
                 getUser·p0.9999: 25.952 ms/op
                 getUser·p1.00:   26.378 ms/op

Iteration   3: 3.273 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.296 ms/op
                 getUser·p0.50:   3.158 ms/op
                 getUser·p0.90:   3.662 ms/op
                 getUser·p0.95:   3.905 ms/op
                 getUser·p0.99:   5.808 ms/op
                 getUser·p0.999:  11.223 ms/op
                 getUser·p0.9999: 21.995 ms/op
                 getUser·p1.00:   25.690 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 306080
  mean =      3.135 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17554 
    [ 2.500,  5.000) = 282758 
    [ 5.000,  7.500) = 4868 
    [ 7.500, 10.000) = 586 
    [10.000, 12.500) = 26 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 135 
    [22.500, 25.000) = 63 
    [25.000, 27.500) = 37 

  Percentiles, ms/op:
      p(0.0000) =      1.161 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.641 ms/op
     p(95.0000) =      3.985 ms/op
     p(99.0000) =      5.759 ms/op
     p(99.9000) =     10.600 ms/op
     p(99.9900) =     25.146 ms/op
     p(99.9990) =     26.208 ms/op
     p(99.9999) =     26.378 ms/op
    p(100.0000) =     26.378 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.002 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 3.926 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.829 ±(99.9%) 0.012 ms/op
Iteration   1: 3.911 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.149 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   4.235 ms/op
                 listUser·p0.95:   4.521 ms/op
                 listUser·p0.99:   6.471 ms/op
                 listUser·p0.999:  18.055 ms/op
                 listUser·p0.9999: 23.855 ms/op
                 listUser·p1.00:   25.559 ms/op

Iteration   2: 4.087 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.417 ms/op
                 listUser·p0.50:   3.908 ms/op
                 listUser·p0.90:   4.628 ms/op
                 listUser·p0.95:   5.325 ms/op
                 listUser·p0.99:   7.643 ms/op
                 listUser·p0.999:  17.172 ms/op
                 listUser·p0.9999: 22.348 ms/op
                 listUser·p1.00:   22.675 ms/op

Iteration   3: 3.983 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.220 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   4.440 ms/op
                 listUser·p0.95:   4.874 ms/op
                 listUser·p0.99:   6.997 ms/op
                 listUser·p0.999:  16.997 ms/op
                 listUser·p0.9999: 25.067 ms/op
                 listUser·p1.00:   25.100 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 240505
  mean =      3.992 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 59 
    [ 2.500,  5.000) = 230013 
    [ 5.000,  7.500) = 8379 
    [ 7.500, 10.000) = 1060 
    [10.000, 12.500) = 461 
    [12.500, 15.000) = 141 
    [15.000, 17.500) = 164 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 108 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      1.149 ms/op
     p(50.0000) =      3.817 ms/op
     p(90.0000) =      4.448 ms/op
     p(95.0000) =      4.866 ms/op
     p(99.0000) =      7.143 ms/op
     p(99.9000) =     17.105 ms/op
     p(99.9900) =     23.953 ms/op
     p(99.9990) =     25.100 ms/op
     p(99.9999) =     25.559 ms/op
    p(100.0000) =     25.559 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score    Error   Units
ClientPb.createUser                      thrpt       3   9.613 ± 21.965  ops/ms
ClientPb.existUser                       thrpt       3  10.851 ±  3.215  ops/ms
ClientPb.getUser                         thrpt       3  10.175 ±  4.180  ops/ms
ClientPb.listUser                        thrpt       3   8.142 ±  2.124  ops/ms
ClientPb.createUser                       avgt       3   3.027 ±  2.958   ms/op
ClientPb.existUser                        avgt       3   3.196 ±  0.868   ms/op
ClientPb.getUser                          avgt       3   3.182 ±  2.083   ms/op
ClientPb.listUser                         avgt       3   3.661 ±  4.702   ms/op
ClientPb.createUser                     sample  301468   3.182 ±  0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.233            ms/op
ClientPb.createUser:createUser·p0.50    sample           3.088            ms/op
ClientPb.createUser:createUser·p0.90    sample           3.621            ms/op
ClientPb.createUser:createUser·p0.95    sample           3.928            ms/op
ClientPb.createUser:createUser·p0.99    sample           5.382            ms/op
ClientPb.createUser:createUser·p0.999   sample          18.907            ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.160            ms/op
ClientPb.createUser:createUser·p1.00    sample          29.819            ms/op
ClientPb.existUser                      sample  314906   3.048 ±  0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.049            ms/op
ClientPb.existUser:existUser·p0.50      sample           2.945            ms/op
ClientPb.existUser:existUser·p0.90      sample           3.473            ms/op
ClientPb.existUser:existUser·p0.95      sample           3.838            ms/op
ClientPb.existUser:existUser·p0.99      sample           5.194            ms/op
ClientPb.existUser:existUser·p0.999     sample          11.856            ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.151            ms/op
ClientPb.existUser:existUser·p1.00      sample          24.248            ms/op
ClientPb.getUser                        sample  306080   3.135 ±  0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.161            ms/op
ClientPb.getUser:getUser·p0.50          sample           3.015            ms/op
ClientPb.getUser:getUser·p0.90          sample           3.641            ms/op
ClientPb.getUser:getUser·p0.95          sample           3.985            ms/op
ClientPb.getUser:getUser·p0.99          sample           5.759            ms/op
ClientPb.getUser:getUser·p0.999         sample          10.600            ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.146            ms/op
ClientPb.getUser:getUser·p1.00          sample          26.378            ms/op
ClientPb.listUser                       sample  240505   3.992 ±  0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.149            ms/op
ClientPb.listUser:listUser·p0.50        sample           3.817            ms/op
ClientPb.listUser:listUser·p0.90        sample           4.448            ms/op
ClientPb.listUser:listUser·p0.95        sample           4.866            ms/op
ClientPb.listUser:listUser·p0.99        sample           7.143            ms/op
ClientPb.listUser:listUser·p0.999       sample          17.105            ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.953            ms/op
ClientPb.listUser:listUser·p1.00        sample          25.559            ms/op
