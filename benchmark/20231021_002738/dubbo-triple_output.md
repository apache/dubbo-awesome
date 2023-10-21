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
# Warmup Iteration   1: 2.454 ops/ms
# Warmup Iteration   2: 5.535 ops/ms
# Warmup Iteration   3: 9.063 ops/ms
Iteration   1: 9.751 ops/ms
Iteration   2: 9.388 ops/ms
Iteration   3: 9.878 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.672 ±(99.9%) 4.638 ops/ms [Average]
  (min, avg, max) = (9.388, 9.672, 9.878), stdev = 0.254
  CI (99.9%): [5.034, 14.310] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 3.712 ops/ms
# Warmup Iteration   2: 9.629 ops/ms
# Warmup Iteration   3: 10.138 ops/ms
Iteration   1: 10.577 ops/ms
Iteration   2: 10.157 ops/ms
Iteration   3: 10.160 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.298 ±(99.9%) 4.412 ops/ms [Average]
  (min, avg, max) = (10.157, 10.298, 10.577), stdev = 0.242
  CI (99.9%): [5.886, 14.710] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.109 ops/ms
# Warmup Iteration   2: 8.619 ops/ms
# Warmup Iteration   3: 9.731 ops/ms
Iteration   1: 9.796 ops/ms
Iteration   2: 10.099 ops/ms
Iteration   3: 9.889 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.928 ±(99.9%) 2.828 ops/ms [Average]
  (min, avg, max) = (9.796, 9.928, 10.099), stdev = 0.155
  CI (99.9%): [7.100, 12.756] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.231 ops/ms
# Warmup Iteration   2: 7.921 ops/ms
# Warmup Iteration   3: 8.303 ops/ms
Iteration   1: 8.391 ops/ms
Iteration   2: 8.441 ops/ms
Iteration   3: 8.429 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.420 ±(99.9%) 0.479 ops/ms [Average]
  (min, avg, max) = (8.391, 8.420, 8.441), stdev = 0.026
  CI (99.9%): [7.941, 8.900] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 8.887 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.509 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.423 ±(99.9%) 0.003 ms/op
Iteration   1: 3.211 ±(99.9%) 0.002 ms/op
Iteration   2: 3.297 ±(99.9%) 0.002 ms/op
Iteration   3: 3.242 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.250 ±(99.9%) 0.794 ms/op [Average]
  (min, avg, max) = (3.211, 3.250, 3.297), stdev = 0.044
  CI (99.9%): [2.456, 4.044] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.349 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.365 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 3.184 ±(99.9%) 0.002 ms/op
Iteration   1: 3.239 ±(99.9%) 0.003 ms/op
Iteration   2: 3.076 ±(99.9%) 0.003 ms/op
Iteration   3: 3.218 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.177 ±(99.9%) 1.611 ms/op [Average]
  (min, avg, max) = (3.076, 3.177, 3.239), stdev = 0.088
  CI (99.9%): [1.567, 4.788] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 8.223 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.447 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 3.271 ±(99.9%) 0.003 ms/op
Iteration   1: 3.243 ±(99.9%) 0.006 ms/op
Iteration   2: 3.210 ±(99.9%) 0.003 ms/op
Iteration   3: 3.247 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.233 ±(99.9%) 0.370 ms/op [Average]
  (min, avg, max) = (3.210, 3.233, 3.247), stdev = 0.020
  CI (99.9%): [2.863, 3.604] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.637 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.028 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.805 ±(99.9%) 0.007 ms/op
Iteration   1: 3.788 ±(99.9%) 0.009 ms/op
Iteration   2: 3.789 ±(99.9%) 0.004 ms/op
Iteration   3: 3.757 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.778 ±(99.9%) 0.337 ms/op [Average]
  (min, avg, max) = (3.757, 3.778, 3.789), stdev = 0.018
  CI (99.9%): [3.441, 4.115] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.168 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 3.706 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.305 ±(99.9%) 0.008 ms/op
Iteration   1: 3.315 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.380 ms/op
                 createUser·p0.50:   3.207 ms/op
                 createUser·p0.90:   3.740 ms/op
                 createUser·p0.95:   4.080 ms/op
                 createUser·p0.99:   6.324 ms/op
                 createUser·p0.999:  17.866 ms/op
                 createUser·p0.9999: 23.135 ms/op
                 createUser·p1.00:   24.379 ms/op

Iteration   2: 3.192 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.376 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.564 ms/op
                 createUser·p0.95:   3.792 ms/op
                 createUser·p0.99:   5.415 ms/op
                 createUser·p0.999:  19.923 ms/op
                 createUser·p0.9999: 22.740 ms/op
                 createUser·p1.00:   24.117 ms/op

Iteration   3: 3.237 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.883 ms/op
                 createUser·p0.50:   3.183 ms/op
                 createUser·p0.90:   3.584 ms/op
                 createUser·p0.95:   3.949 ms/op
                 createUser·p0.99:   5.424 ms/op
                 createUser·p0.999:  13.808 ms/op
                 createUser·p0.9999: 24.583 ms/op
                 createUser·p1.00:   24.969 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 295641
  mean =      3.247 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13470 
    [ 2.500,  5.000) = 277037 
    [ 5.000,  7.500) = 3724 
    [ 7.500, 10.000) = 718 
    [10.000, 12.500) = 323 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 78 
    [20.000, 22.500) = 123 
    [22.500, 25.000) = 69 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.883 ms/op
     p(50.0000) =      3.154 ms/op
     p(90.0000) =      3.633 ms/op
     p(95.0000) =      3.940 ms/op
     p(99.0000) =      6.038 ms/op
     p(99.9000) =     16.679 ms/op
     p(99.9900) =     23.851 ms/op
     p(99.9990) =     24.841 ms/op
     p(99.9999) =     24.969 ms/op
    p(100.0000) =     24.969 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.175 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 3.346 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.104 ±(99.9%) 0.007 ms/op
Iteration   1: 3.070 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.996 ms/op
                 existUser·p0.50:   2.998 ms/op
                 existUser·p0.90:   3.269 ms/op
                 existUser·p0.95:   3.518 ms/op
                 existUser·p0.99:   5.587 ms/op
                 existUser·p0.999:  7.927 ms/op
                 existUser·p0.9999: 21.594 ms/op
                 existUser·p1.00:   22.086 ms/op

Iteration   2: 3.210 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.073 ms/op
                 existUser·p0.50:   3.158 ms/op
                 existUser·p0.90:   3.568 ms/op
                 existUser·p0.95:   3.895 ms/op
                 existUser·p0.99:   5.652 ms/op
                 existUser·p0.999:  13.977 ms/op
                 existUser·p0.9999: 20.939 ms/op
                 existUser·p1.00:   21.856 ms/op

Iteration   3: 3.169 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.612 ms/op
                 existUser·p0.50:   3.138 ms/op
                 existUser·p0.90:   3.473 ms/op
                 existUser·p0.95:   3.736 ms/op
                 existUser·p0.99:   5.513 ms/op
                 existUser·p0.999:  14.090 ms/op
                 existUser·p0.9999: 21.024 ms/op
                 existUser·p1.00:   22.020 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 304544
  mean =      3.149 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20632 
    [ 2.500,  5.000) = 278585 
    [ 5.000,  7.500) = 4638 
    [ 7.500, 10.000) = 323 
    [10.000, 12.500) = 63 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 112 
    [20.000, 22.500) = 112 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.996 ms/op
     p(50.0000) =      3.105 ms/op
     p(90.0000) =      3.461 ms/op
     p(95.0000) =      3.744 ms/op
     p(99.0000) =      5.591 ms/op
     p(99.9000) =     12.409 ms/op
     p(99.9900) =     21.186 ms/op
     p(99.9990) =     22.020 ms/op
     p(99.9999) =     22.086 ms/op
    p(100.0000) =     22.086 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.346 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.403 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.405 ±(99.9%) 0.010 ms/op
Iteration   1: 3.228 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.260 ms/op
                 getUser·p0.50:   3.101 ms/op
                 getUser·p0.90:   3.555 ms/op
                 getUser·p0.95:   3.805 ms/op
                 getUser·p0.99:   5.996 ms/op
                 getUser·p0.999:  19.366 ms/op
                 getUser·p0.9999: 24.052 ms/op
                 getUser·p1.00:   24.052 ms/op

Iteration   2: 3.223 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.356 ms/op
                 getUser·p0.50:   3.158 ms/op
                 getUser·p0.90:   3.572 ms/op
                 getUser·p0.95:   3.727 ms/op
                 getUser·p0.99:   5.308 ms/op
                 getUser·p0.999:  14.351 ms/op
                 getUser·p0.9999: 23.790 ms/op
                 getUser·p1.00:   24.642 ms/op

Iteration   3: 3.269 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.949 ms/op
                 getUser·p0.50:   3.203 ms/op
                 getUser·p0.90:   3.625 ms/op
                 getUser·p0.95:   4.039 ms/op
                 getUser·p0.99:   5.947 ms/op
                 getUser·p0.999:  9.443 ms/op
                 getUser·p0.9999: 21.608 ms/op
                 getUser·p1.00:   22.675 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 296103
  mean =      3.240 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11204 
    [ 2.500,  5.000) = 279184 
    [ 5.000,  7.500) = 4816 
    [ 7.500, 10.000) = 338 
    [10.000, 12.500) = 190 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 84 
    [20.000, 22.500) = 148 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.949 ms/op
     p(50.0000) =      3.162 ms/op
     p(90.0000) =      3.580 ms/op
     p(95.0000) =      3.826 ms/op
     p(99.0000) =      5.882 ms/op
     p(99.9000) =     15.301 ms/op
     p(99.9900) =     23.389 ms/op
     p(99.9990) =     24.381 ms/op
     p(99.9999) =     24.642 ms/op
    p(100.0000) =     24.642 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.075 ±(99.9%) 0.130 ms/op
# Warmup Iteration   2: 4.149 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.890 ±(99.9%) 0.012 ms/op
Iteration   1: 3.847 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.565 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   4.153 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   6.767 ms/op
                 listUser·p0.999:  14.746 ms/op
                 listUser·p0.9999: 18.209 ms/op
                 listUser·p1.00:   19.956 ms/op

Iteration   2: 3.850 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.253 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   4.166 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   6.930 ms/op
                 listUser·p0.999:  13.304 ms/op
                 listUser·p0.9999: 16.220 ms/op
                 listUser·p1.00:   17.138 ms/op

Iteration   3: 3.831 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.958 ms/op
                 listUser·p0.50:   3.707 ms/op
                 listUser·p0.90:   4.145 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   6.865 ms/op
                 listUser·p0.999:  12.911 ms/op
                 listUser·p0.9999: 14.461 ms/op
                 listUser·p1.00:   14.746 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 249663
  mean =      3.843 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 55 
    [ 2.500,  3.750) = 130405 
    [ 3.750,  5.000) = 111674 
    [ 5.000,  6.250) = 2687 
    [ 6.250,  7.500) = 3162 
    [ 7.500,  8.750) = 832 
    [ 8.750, 10.000) = 169 
    [10.000, 11.250) = 77 
    [11.250, 12.500) = 176 
    [12.500, 13.750) = 247 
    [13.750, 15.000) = 71 
    [15.000, 16.250) = 63 
    [16.250, 17.500) = 25 
    [17.500, 18.750) = 16 

  Percentiles, ms/op:
      p(0.0000) =      1.565 ms/op
     p(50.0000) =      3.731 ms/op
     p(90.0000) =      4.153 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      6.824 ms/op
     p(99.9000) =     13.255 ms/op
     p(99.9900) =     17.335 ms/op
     p(99.9990) =     19.727 ms/op
     p(99.9999) =     19.956 ms/op
    p(100.0000) =     19.956 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.672 ± 4.638  ops/ms
ClientPb.existUser                       thrpt       3  10.298 ± 4.412  ops/ms
ClientPb.getUser                         thrpt       3   9.928 ± 2.828  ops/ms
ClientPb.listUser                        thrpt       3   8.420 ± 0.479  ops/ms
ClientPb.createUser                       avgt       3   3.250 ± 0.794   ms/op
ClientPb.existUser                        avgt       3   3.177 ± 1.611   ms/op
ClientPb.getUser                          avgt       3   3.233 ± 0.370   ms/op
ClientPb.listUser                         avgt       3   3.778 ± 0.337   ms/op
ClientPb.createUser                     sample  295641   3.247 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.883           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.154           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.633           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.940           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.038           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.679           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.851           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.969           ms/op
ClientPb.existUser                      sample  304544   3.149 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.996           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.105           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.461           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.744           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.591           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.409           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.186           ms/op
ClientPb.existUser:existUser·p1.00      sample          22.086           ms/op
ClientPb.getUser                        sample  296103   3.240 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.949           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.162           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.580           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.826           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.882           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.301           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.389           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.642           ms/op
ClientPb.listUser                       sample  249663   3.843 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.565           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.731           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.153           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.358           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.824           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.255           ms/op
ClientPb.listUser:listUser·p0.9999      sample          17.335           ms/op
ClientPb.listUser:listUser·p1.00        sample          19.956           ms/op
