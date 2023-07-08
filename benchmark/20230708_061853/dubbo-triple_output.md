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
# Warmup Iteration   1: 1.376 ops/ms
# Warmup Iteration   2: 3.541 ops/ms
# Warmup Iteration   3: 6.892 ops/ms
Iteration   1: 7.090 ops/ms
Iteration   2: 7.598 ops/ms
Iteration   3: 7.716 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.468 ±(99.9%) 6.069 ops/ms [Average]
  (min, avg, max) = (7.090, 7.468, 7.716), stdev = 0.333
  CI (99.9%): [1.399, 13.537] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:12
# Fork: 1 of 1
# Warmup Iteration   1: 2.524 ops/ms
# Warmup Iteration   2: 6.442 ops/ms
# Warmup Iteration   3: 7.774 ops/ms
Iteration   1: 8.439 ops/ms
Iteration   2: 8.079 ops/ms
Iteration   3: 8.198 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.239 ±(99.9%) 3.354 ops/ms [Average]
  (min, avg, max) = (8.079, 8.239, 8.439), stdev = 0.184
  CI (99.9%): [4.885, 11.592] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:05
# Fork: 1 of 1
# Warmup Iteration   1: 2.063 ops/ms
# Warmup Iteration   2: 6.258 ops/ms
# Warmup Iteration   3: 7.580 ops/ms
Iteration   1: 8.000 ops/ms
Iteration   2: 7.685 ops/ms
Iteration   3: 7.392 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.692 ±(99.9%) 5.542 ops/ms [Average]
  (min, avg, max) = (7.392, 7.692, 8.000), stdev = 0.304
  CI (99.9%): [2.150, 13.234] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:59
# Fork: 1 of 1
# Warmup Iteration   1: 1.958 ops/ms
# Warmup Iteration   2: 5.176 ops/ms
# Warmup Iteration   3: 6.345 ops/ms
Iteration   1: 6.296 ops/ms
Iteration   2: 6.485 ops/ms
Iteration   3: 6.781 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.521 ±(99.9%) 4.455 ops/ms [Average]
  (min, avg, max) = (6.296, 6.521, 6.781), stdev = 0.244
  CI (99.9%): [2.066, 10.975] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:52
# Fork: 1 of 1
# Warmup Iteration   1: 13.673 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 4.914 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.269 ±(99.9%) 0.005 ms/op
Iteration   1: 4.182 ±(99.9%) 0.008 ms/op
Iteration   2: 3.981 ±(99.9%) 0.012 ms/op
Iteration   3: 4.221 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.128 ±(99.9%) 2.353 ms/op [Average]
  (min, avg, max) = (3.981, 4.128, 4.221), stdev = 0.129
  CI (99.9%): [1.775, 6.481] (assumes normal distribution)


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
# Warmup Iteration   1: 13.358 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 4.616 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.203 ±(99.9%) 0.005 ms/op
Iteration   1: 4.000 ±(99.9%) 0.009 ms/op
Iteration   2: 3.894 ±(99.9%) 0.005 ms/op
Iteration   3: 3.973 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.956 ±(99.9%) 1.007 ms/op [Average]
  (min, avg, max) = (3.894, 3.956, 4.000), stdev = 0.055
  CI (99.9%): [2.949, 4.963] (assumes normal distribution)


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
# Warmup Iteration   1: 15.077 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 4.836 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.168 ±(99.9%) 0.012 ms/op
Iteration   1: 4.167 ±(99.9%) 0.006 ms/op
Iteration   2: 4.132 ±(99.9%) 0.005 ms/op
Iteration   3: 4.143 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.147 ±(99.9%) 0.327 ms/op [Average]
  (min, avg, max) = (4.132, 4.147, 4.167), stdev = 0.018
  CI (99.9%): [3.820, 4.474] (assumes normal distribution)


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
# Warmup Iteration   1: 16.205 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 6.070 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.906 ±(99.9%) 0.006 ms/op
Iteration   1: 4.820 ±(99.9%) 0.009 ms/op
Iteration   2: 4.657 ±(99.9%) 0.019 ms/op
Iteration   3: 4.799 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.759 ±(99.9%) 1.618 ms/op [Average]
  (min, avg, max) = (4.657, 4.759, 4.820), stdev = 0.089
  CI (99.9%): [3.141, 6.376] (assumes normal distribution)


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
# Warmup Iteration   1: 13.678 ±(99.9%) 0.200 ms/op
# Warmup Iteration   2: 5.200 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 4.627 ±(99.9%) 0.020 ms/op
Iteration   1: 4.210 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   2.034 ms/op
                 createUser·p0.50:   3.973 ms/op
                 createUser·p0.90:   5.120 ms/op
                 createUser·p0.95:   5.997 ms/op
                 createUser·p0.99:   9.175 ms/op
                 createUser·p0.999:  22.153 ms/op
                 createUser·p0.9999: 25.946 ms/op
                 createUser·p1.00:   26.444 ms/op

Iteration   2: 4.146 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.522 ms/op
                 createUser·p0.50:   3.940 ms/op
                 createUser·p0.90:   4.940 ms/op
                 createUser·p0.95:   5.505 ms/op
                 createUser·p0.99:   7.496 ms/op
                 createUser·p0.999:  16.494 ms/op
                 createUser·p0.9999: 27.066 ms/op
                 createUser·p1.00:   27.558 ms/op

Iteration   3: 4.219 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.966 ms/op
                 createUser·p0.50:   3.949 ms/op
                 createUser·p0.90:   5.046 ms/op
                 createUser·p0.95:   5.833 ms/op
                 createUser·p0.99:   8.700 ms/op
                 createUser·p0.999:  23.738 ms/op
                 createUser·p0.9999: 35.324 ms/op
                 createUser·p1.00:   41.091 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 228854
  mean =      4.191 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 205393 
    [ 5.000, 10.000) = 22417 
    [10.000, 15.000) = 672 
    [15.000, 20.000) = 88 
    [20.000, 25.000) = 143 
    [25.000, 30.000) = 131 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 7 
    [40.000, 45.000) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.522 ms/op
     p(50.0000) =      3.953 ms/op
     p(90.0000) =      5.022 ms/op
     p(95.0000) =      5.775 ms/op
     p(99.0000) =      8.421 ms/op
     p(99.9000) =     22.381 ms/op
     p(99.9900) =     27.984 ms/op
     p(99.9990) =     41.072 ms/op
     p(99.9999) =     41.091 ms/op
    p(100.0000) =     41.091 ms/op


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
# Warmup Iteration   1: 11.415 ±(99.9%) 0.161 ms/op
# Warmup Iteration   2: 4.915 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 4.034 ±(99.9%) 0.014 ms/op
Iteration   1: 4.028 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.790 ms/op
                 existUser·p0.50:   3.850 ms/op
                 existUser·p0.90:   4.710 ms/op
                 existUser·p0.95:   5.390 ms/op
                 existUser·p0.99:   8.045 ms/op
                 existUser·p0.999:  11.364 ms/op
                 existUser·p0.9999: 25.954 ms/op
                 existUser·p1.00:   27.132 ms/op

Iteration   2: 3.832 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.198 ms/op
                 existUser·p0.50:   3.764 ms/op
                 existUser·p0.90:   4.071 ms/op
                 existUser·p0.95:   4.506 ms/op
                 existUser·p0.99:   7.668 ms/op
                 existUser·p0.999:  26.914 ms/op
                 existUser·p0.9999: 32.834 ms/op
                 existUser·p1.00:   33.456 ms/op

Iteration   3: 3.910 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.079 ms/op
                 existUser·p0.50:   3.789 ms/op
                 existUser·p0.90:   4.424 ms/op
                 existUser·p0.95:   4.948 ms/op
                 existUser·p0.99:   7.250 ms/op
                 existUser·p0.999:  11.684 ms/op
                 existUser·p0.9999: 33.379 ms/op
                 existUser·p1.00:   34.013 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 244775
  mean =      3.922 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 415 
    [ 2.500,  5.000) = 231978 
    [ 5.000,  7.500) = 9817 
    [ 7.500, 10.000) = 2002 
    [10.000, 12.500) = 300 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 42 
    [27.500, 30.000) = 55 
    [30.000, 32.500) = 52 
    [32.500, 35.000) = 33 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.079 ms/op
     p(50.0000) =      3.789 ms/op
     p(90.0000) =      4.424 ms/op
     p(95.0000) =      5.014 ms/op
     p(99.0000) =      7.619 ms/op
     p(99.9000) =     19.963 ms/op
     p(99.9900) =     32.866 ms/op
     p(99.9990) =     33.882 ms/op
     p(99.9999) =     34.013 ms/op
    p(100.0000) =     34.013 ms/op


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
# Warmup Iteration   1: 14.201 ±(99.9%) 0.221 ms/op
# Warmup Iteration   2: 4.936 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.190 ±(99.9%) 0.013 ms/op
Iteration   1: 4.178 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   2.367 ms/op
                 getUser·p0.50:   3.990 ms/op
                 getUser·p0.90:   4.874 ms/op
                 getUser·p0.95:   5.874 ms/op
                 getUser·p0.99:   8.503 ms/op
                 getUser·p0.999:  17.465 ms/op
                 getUser·p0.9999: 26.565 ms/op
                 getUser·p1.00:   27.361 ms/op

Iteration   2: 4.150 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   2.396 ms/op
                 getUser·p0.50:   3.973 ms/op
                 getUser·p0.90:   4.792 ms/op
                 getUser·p0.95:   5.358 ms/op
                 getUser·p0.99:   7.709 ms/op
                 getUser·p0.999:  25.706 ms/op
                 getUser·p0.9999: 34.622 ms/op
                 getUser·p1.00:   35.652 ms/op

Iteration   3: 3.980 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   2.359 ms/op
                 getUser·p0.50:   3.846 ms/op
                 getUser·p0.90:   4.522 ms/op
                 getUser·p0.95:   4.825 ms/op
                 getUser·p0.99:   6.824 ms/op
                 getUser·p0.999:  11.196 ms/op
                 getUser·p0.9999: 31.160 ms/op
                 getUser·p1.00:   32.047 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 234070
  mean =      4.101 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 55 
    [ 2.500,  5.000) = 218560 
    [ 5.000,  7.500) = 12704 
    [ 7.500, 10.000) = 2081 
    [10.000, 12.500) = 326 
    [12.500, 15.000) = 78 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 75 
    [27.500, 30.000) = 61 
    [30.000, 32.500) = 35 
    [32.500, 35.000) = 26 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      2.359 ms/op
     p(50.0000) =      3.944 ms/op
     p(90.0000) =      4.702 ms/op
     p(95.0000) =      5.267 ms/op
     p(99.0000) =      7.766 ms/op
     p(99.9000) =     17.496 ms/op
     p(99.9900) =     33.312 ms/op
     p(99.9990) =     35.498 ms/op
     p(99.9999) =     35.652 ms/op
    p(100.0000) =     35.652 ms/op


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
# Warmup Iteration   1: 16.742 ±(99.9%) 0.269 ms/op
# Warmup Iteration   2: 6.214 ±(99.9%) 0.039 ms/op
# Warmup Iteration   3: 5.169 ±(99.9%) 0.020 ms/op
Iteration   1: 5.076 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   2.580 ms/op
                 listUser·p0.50:   4.751 ms/op
                 listUser·p0.90:   5.874 ms/op
                 listUser·p0.95:   7.037 ms/op
                 listUser·p0.99:   9.650 ms/op
                 listUser·p0.999:  26.880 ms/op
                 listUser·p0.9999: 30.540 ms/op
                 listUser·p1.00:   31.982 ms/op

Iteration   2: 4.920 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.005 ms/op
                 listUser·p0.50:   4.669 ms/op
                 listUser·p0.90:   5.521 ms/op
                 listUser·p0.95:   6.455 ms/op
                 listUser·p0.99:   9.650 ms/op
                 listUser·p0.999:  24.466 ms/op
                 listUser·p0.9999: 28.705 ms/op
                 listUser·p1.00:   29.098 ms/op

Iteration   3: 5.009 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.355 ms/op
                 listUser·p0.50:   4.776 ms/op
                 listUser·p0.90:   5.620 ms/op
                 listUser·p0.95:   6.799 ms/op
                 listUser·p0.99:   9.552 ms/op
                 listUser·p0.999:  18.026 ms/op
                 listUser·p0.9999: 21.301 ms/op
                 listUser·p1.00:   22.774 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 191994
  mean =      5.001 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9 
    [ 2.500,  5.000) = 132878 
    [ 5.000,  7.500) = 52122 
    [ 7.500, 10.000) = 5459 
    [10.000, 12.500) = 842 
    [12.500, 15.000) = 229 
    [15.000, 17.500) = 109 
    [17.500, 20.000) = 91 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 102 
    [27.500, 30.000) = 48 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.005 ms/op
     p(50.0000) =      4.727 ms/op
     p(90.0000) =      5.693 ms/op
     p(95.0000) =      6.791 ms/op
     p(99.0000) =      9.634 ms/op
     p(99.9000) =     24.085 ms/op
     p(99.9900) =     29.229 ms/op
     p(99.9990) =     31.861 ms/op
     p(99.9999) =     31.982 ms/op
    p(100.0000) =     31.982 ms/op


# Run complete. Total time: 00:13:19

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.468 ± 6.069  ops/ms
ClientPb.existUser                       thrpt       3   8.239 ± 3.354  ops/ms
ClientPb.getUser                         thrpt       3   7.692 ± 5.542  ops/ms
ClientPb.listUser                        thrpt       3   6.521 ± 4.455  ops/ms
ClientPb.createUser                       avgt       3   4.128 ± 2.353   ms/op
ClientPb.existUser                        avgt       3   3.956 ± 1.007   ms/op
ClientPb.getUser                          avgt       3   4.147 ± 0.327   ms/op
ClientPb.listUser                         avgt       3   4.759 ± 1.618   ms/op
ClientPb.createUser                     sample  228854   4.191 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.522           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.953           ms/op
ClientPb.createUser:createUser·p0.90    sample           5.022           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.775           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.421           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.381           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.984           ms/op
ClientPb.createUser:createUser·p1.00    sample          41.091           ms/op
ClientPb.existUser                      sample  244775   3.922 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.079           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.789           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.424           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.014           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.619           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.963           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.866           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.013           ms/op
ClientPb.getUser                        sample  234070   4.101 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.359           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.944           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.702           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.267           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.766           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.496           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.312           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.652           ms/op
ClientPb.listUser                       sample  191994   5.001 ± 0.010   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.005           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.727           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.693           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.791           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.634           ms/op
ClientPb.listUser:listUser·p0.999       sample          24.085           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.229           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.982           ms/op
